Нужно для компьютеров учебных учреждений с целью ограничения доступа к нежелательным функциям.
Настройки находятся на рабочем столе студенческого пользователя (`.config/kdeglobals`)
```c
[KDE Resource Restrictions][$i]
# Отключает возможность изменения обоев рабочего стола
wallpaper=false
[KDE Action Restrictions][$i]
# Запрещает редактирование значков рабочего стола
editable_desktop_icons=false
# Отключает возможность блокировки экрана
action/lock_screen=false
# Отключает возможность создания новой сессии
action/start_new_session=false
# Отключает переключение пользователей
action/switch_user=false
# Скрывает опцию показа панели инструментов
action/options_show_toolbar=false
# Запрещает перемещение панелей инструментов
movable_toolbars=false
# Отключает возможность разблокировки рабочего стола
plasma/plasmashell/unlockedDesktop=false
# Запрещает конфигурацию рабочего стола при его блокировке
plasma/plasmashell/allow_configure_when_locked=false
# Отключает контекстное меню оболочки плазмы
plasma/plasmashell/containment_context_menu=false
# Запрещает действия в контекстных меню
plasma/containment_actions=false
# Отключает возможность настройки горячих клавиш
action/options_configure_keybinding=false
# Отключает настройку панелей инструментов
action/options_configure_toolbars=false
# Отключает настройку уведомлений
action/options_configure_notifications=false
# Отключает доступ к настройке рабочего стола
action/configdesktop=false
# Отключает изменение размера значков на рабочем столе
action/incIconSize=false
action/decIconSize=false
# Отключает возможность изменения шрифтов
action/font=false
# Отключает контекстное меню для панели меню (Kickoff)
action/kicker_rmb=false
# Отключает контекстное меню для рабочего стола
action/kdesktop_rmb=true
# Отключает доступ к настройкам
action/settings=false
# Отключает использование данных приложений рабочего стола
appdata_kdesktop=false
[KDE Control Module Restrictions][$i]
# Отключает доступ к системным настройкам
systemsettings.desktop=false
# Отключает модуль специальных возможностей
kcm_access.desktop=false
# Отключает модуль настройки цветов
kcm_colors.desktop=false
# Отключает модуль темы рабочего стола
kcm_desktoptheme.desktop=false
# Отключает настройки рабочей среды
kcm_workspace.desktop=false
# Отключает настройки файлового индекса Baloo
kcm_baloofile.desktop=false
# Отключает настройки клавиш
kcm_keys.desktop=false
# Отключает модуль настройки шрифтов
kcm_fonts.desktop=false
# Отключает модуль уведомлений
kcm_notifications.desktop=false
# Отключает управление пользователями
kcm_users.desktop=false
# Отключает настройки языка
kcm_translations.desktop=false
# Отключает модуль настройки тачпада
kcm_touchpad.desktop=false
# Отключает модуль стилей интерфейса
kcm_style.desktop=false
# Отключает заставки при входе
kcm_splashscreen.desktop=false
# Отключает настройки диспетчера входа (SDDM)
kcm_sddm.desktop=false
# Отключает настройку значков
kcm_icons.desktop=false
# Отключает общие настройки внешнего вида
kcm_lookandfeel.desktop=false
# Отключает настройки сессий
kcm_smserver.desktop=false
# Отключает начальную страницу настроек
kcm_landingpage.desktop=false
# Отключает настройки ночного режима
kcm_nightcolor.desktop=false
# Отключает настройки указателя мыши
kcm_cursortheme.desktop=false
# Отключает настройки форматов (даты, чисел и пр.)
kcm_formats.desktop=false
# Отключает настройки автозапуска приложений
kcm_autostart.desktop=false
# Отключает настройки Bluetooth
kcm_bluetooth.desktop=false
# Отключает выбор компонентов приложений
kcm_componentchooser.desktop=false
# Отключает настройки обратной связи при запуске приложений
kcm_launchfeedback.desktop=false
# Отключает настройки цветовой калибровки
kcm_kgamma.desktop=false
# Отключает управление демонами KDE
kcm_kded.desktop=false
# Отключает настройки часов
kcm_clock.desktop=false
# Отключает модуль работы с камерой
kamera.desktop=false
# Отключает настройки типов файлов
kcm_filetypes.desktop=false
# Отключает настройки активности
kcm_activities.desktop=false
# Отключает настройки интерфейса QtQuick
kcm_qtquicksettings.desktop=false
# Отключает управление принтерами
kcm_printer_manager.desktop=false
# Отключает настройку путей в файловой системе
kcm_desktoppaths.desktop=false
# Отключает модуль установки шрифтов
kcm_fontinst.desktop=false
# Отключает настройки PCI устройств
kcm_pci.desktop=false
# Отключает настройки прерываний
kcm_interrupts.desktop=false
# Отключает настройки для аудио CD
kcm_audiocd.desktop=false
# Отключает настройки учетных записей
kcm_kaccounts.desktop=false
# Отключает KDiskFree
kcm_kdf.desktop=false
# Отключает горячие клавиши
kcm_hotkeys.desktop=false
# Отключает настройки блокировки экрана
kcm_screenlocker.desktop=false
```
