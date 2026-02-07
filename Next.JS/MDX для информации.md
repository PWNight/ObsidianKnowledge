Источник: https://nextjs.org/docs/app/guides/mdx
## Описание
Markdown - облегчённый язык разметки, используемый для форматирования текста. Позволяет писать обычный текст, который затем преобразуется в HTML разметку.

MDX - установка поверх Markdown, позволяющая писать JSX непосредственно в файлах Markdown.

Next.js поддерживает как локальный MDX-контент внутри вашего приложения, так и удалённые MDX-файлы, динамически загружаемые на сервер. Плагин Next.js преобразует компоненты Markdown и React в HTML, включая поддержку использования в серверных компонентах (по умолчанию в App Router).

## Установка и настройка
Для установки MDX введите:
```ts
npm install @next/mdx @mdx-js/loader @mdx-js/react @types/mdx
```

Далее обновите `next.config.mjs`, приведя его к примерно такому виду:
```ts
import createMDX from '@next/mdx'

/** @type {import('next').NextConfig} */
const nextConfig = {
  // Configure `pageExtensions` to include markdown and MDX files
  pageExtensions: ['js', 'jsx', 'md', 'mdx', 'ts', 'tsx'],
  // Optionally, add any other Next.js config below
}
 
const withMDX = createMDX({
  // Add markdown plugins here, as desired
})
 
// Merge MDX config with Next.js config
export default withMDX(nextConfig)
```

Чтобы обрабатывать и `.md` формат, обновите `withMDX`:
```ts
const withMDX = createMDX({ extension: /\.(md|mdx)$/,})
```

**ДОПИСАТЬ**