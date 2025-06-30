# motors

## Описание

**motors** — это веб-приложение для отображения и аренды мотоциклов. Интерфейс реализован с помощью HTML и SCSS/CSS, а для стилизации используется TailwindCSS. Приложение отображает карточки мотоциклов с информацией о пробеге, стоимости аренды и уровнем масла, а также содержит стилизованные элементы управления.

> Верстка выполнена по макету Pixso: [https://pixso.net/app/editor/8uPI2idLxSnEVg3HSycq6A](https://pixso.net/app/editor/8uPI2idLxSnEVg3HSycq6A)

## Стэк

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=fff)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=fff)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=fff)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=fff)

## Структура проекта

- `app/` — основные HTML-файлы и стили
  - `index.html` — главная страница приложения
  - `styles/` — SCSS и CSS стили, разбитые по компонентам (кнопки, карточки, прогресс-бары и т.д.)
- `pages/` — дополнительные страницы (папки для будущих разделов)
- `shared/` — изображения и иконки, используемые в приложении
- `package.json` — зависимости для сборки стилей (TailwindCSS)

## Установка и запуск

1. Установите зависимости для сборки стилей:
   ```bash
   npm install
   ```
2. Скомпилируйте стили (если требуется):
   ```bash
   npx tailwindcss -i ./app/styles/input.css -o ./app/styles/output.css --watch
   ```
   Или используйте аналогичную команду для вашей конфигурации.
3. Откройте файл `app/index.html` в браузере.

> Приложение работает как статический сайт, сервер не требуется.

## Лицензия

Проект распространяется под лицензией MIT. Подробнее см. файл LICENSE.
