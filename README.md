# 40 карточек

Frontend-игра на React и Vite с сорока интерактивными карточками.

## Установка и запуск

```bash
npm install
npm run dev
```

Откройте адрес, который покажет Vite, обычно `http://localhost:5173`.

## Проверка production-сборки

```bash
npm run build
npm run preview
```

Папка результата сборки: `dist`.

## Изменение вопросов

Отредактируйте `src/data/questions.json`. Должно быть ровно 40 объектов с уникальными `id` от 1 до 40 и непустыми полями `question` и `answer`.

## Публикация на GitHub

```bash
git init
git add .
git commit -m "Create 40 cards game"
git branch -M main
git remote add origin <URL_REPOSITORY>
git push -u origin main
```

На Vercel выберите `Add New Project`, импортируйте репозиторий GitHub и оставьте настройки Vite: Build Command `npm run build`, Output Directory `dist`.
