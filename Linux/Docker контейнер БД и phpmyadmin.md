```yml
# We're using version 3.7 of the Docker Compose file format
version: "3.7"

# Define services/containers
services:
  # MySQL container
  mysql:
    restart: always
    image: mysql
    # Connect to "my-network" network, as defined below
    networks:
      - my-network
    # Pass a list of environment variables to the container
    environment:
      MYSQL_ROOT_PASSWORD: root

  # phpMyAdmin container
  phpmyadmin:
    restart: always
    image: phpmyadmin/phpmyadmin
    # Connect to "my-network" network, as defined below
    networks:
      - my-network
    # Map port 8080 on the host to port 80 inside the container
    # Syntax is: "HOST_PORT:CONTAINER_PORT"
    ports:
      - "8080:80"
    # Pass a list of environment variables to the container
    environment:
      PMA_HOST: mysql
    # Wait for "mysql" container to start first
    depends_on:
      - mysql

# Define networks
networks:
  my-network:
```