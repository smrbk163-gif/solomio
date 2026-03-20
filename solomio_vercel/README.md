# Соло Мио — Школа вокала в Самаре

## Структура проекта

```
/
├── index.html      ← весь сайт (HTML + CSS + JS встроены)
├── sitemap.xml     ← для поисковиков
├── robots.txt      ← для поисковиков
├── vercel.json     ← конфигурация Vercel
└── README.md
```

## Деплой на Vercel

### Способ 1 — Drag & Drop (быстрее всего)
1. Открой https://vercel.com/new
2. Перетащи папку проекта целиком
3. Нажми Deploy

### Способ 2 — GitHub
1. Создай репозиторий на GitHub
2. Загрузи все файлы
3. В Vercel: New Project → Import Git Repository

## Внешние зависимости (CDN — интернет нужен)
- **Google Fonts** — Cormorant Garamond + DM Sans
- **Anthropic API** — блок "Проверь свой голос" (нужен API-ключ на сервере)

## После деплоя
- Обнови URL в `index.html`: найди `solomiosamara.ru` → замени на свой домен
- Обнови URL в `sitemap.xml`
- Добавь домен в Vercel Settings → Domains
