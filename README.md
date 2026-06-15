# Для тебя ♡

Личный сайт с паролем — открывается по QR-коду.

## Как настроить

1. Открой `index.html` и измени:
   - **Пароль** — строка `const PASSWORD = 'ваш_пароль';`
   - **Текст поздравления** — блок `<div class="letter">`
   - **Заголовок** — тег `<h1>` внутри `#content`
2. **Фото** (необязательно): положи файл `images/photo.jpg`. Если фото не нужно — удали тег `<img>` в `index.html`.

## Как выложить на GitHub и получить ссылку

1. Создай новый репозиторий на [github.com/new](https://github.com/new) (например, `letter-for-d`).
2. В терминале, из папки проекта:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ВАШ_НИК/letter-for-d.git
git push -u origin main
```

3. На GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root)** → Save.
4. Через 1–2 минуты сайт будет доступен по адресу:

```
https://ВАШ_НИК.github.io/letter-for-d/
```

Эту ссылку вставь в генератор QR-кода (например, [qr.io](https://qr.io)).
