# ISNUR — лендинг

Статический одностраничный сайт ISNUR (инженерное строительство). Mobile-first, 3D-сцена на three.js (подключается с CDN), без сборки.

## Структура
- `index.html` — весь сайт (HTML, CSS, JS)
- `favicon.svg` — иконка
- `vercel.json` — настройки Vercel

## Деплой на Vercel
Vercel → Add New → Project → импортировать этот репозиторий → Framework Preset: **Other** → Deploy.
Сборка не нужна: Build Command и Output Directory оставить пустыми.

## Что заменить перед запуском
- Телефон, WhatsApp/Telegram, почта, адрес (поиск по `XXX` и `[`)
- Карточки объектов (раздел «Объекты»)
- Отправка формы (сейчас демо-режим)
