# GlassTube

<p align="center">
  <a href="https://google.com/chrome"><img src="https://img.shields.io/badge/Платформа-Web-0078D6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Платформа"></a>
  <a href="https://krezibro.github.io/glasstube/"><img src="https://img.shields.io/badge/Демо-Online-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="Демо онлайн"></a>
  <a href="https://developer.mozilla.org/ru/docs/Web/CSS"><img src="https://img.shields.io/badge/Стиль-Glassmorphism-9945FF?style=for-the-badge&logo=css3&logoColor=white" alt="Стиль"></a>
  <a href="https://developer.mozilla.org/ru/docs/Web/JavaScript"><img src="https://img.shields.io/badge/Зависимости-Zero_Dependencies-00B359?style=for-the-badge&logo=javascript&logoColor=white" alt="Зависимости"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/Лицензия-MIT-gray?style=for-the-badge" alt="Лицензия"></a>
</p>

Концепт современного веб-интерфейса видеохостинга в стиле **Glassmorphism** (эффект матового стекла), вдохновленный дизайном YouTube. Реализован в виде ультралегковесного автономного Single-Page приложения на чистом HTML, CSS и Vanilla JavaScript без внешних фреймворков и сборщиков.

Мгновенный отклик интерфейса, плавная адаптивность под любые диагонали экранов, мягкие размытия и нулевой оверхед — файл полностью самодостаточен и весит менее 25 КБ.

## Основные возможности

* **Glassmorphism дизайн**: Полупрозрачные панели с аппаратным размытием фона (`backdrop-filter`), мягкие градиентные свечения, объемные блики и плавные тени.
* **Тёмная и светлая темы**: Интеллектуальное автоопределение системной темы оформления с возможностью мгновенного ручного переключения по клику в шапке.
* **Интерактивный плеер**: Динамический режим воспроизведения видео с автоматическим обновлением информации (название, автор, счетчики просмотров и рекомендательный блок).
* **Модальное окно «Поделиться»**: Встроенный диалог шаринга с быстрым копированием ссылки в буфер обмена, чекбоксом привязки таймкода и шорткатами популярных соцсетей.
* **Полная адаптивность**: Безупречное отображение на ультрашироких мониторах, ноутбуках, планшетах и смартфонах (с поддержкой `safe-area-inset` для экранов с вырезами).
* **Zero Dependencies**: Никаких сторонних библиотек, npm-пакетов или тяжелых бандлеров — открывается сразу в любом браузере.

## Стек технологий

* **HTML5**: Семантическая верстка, инлайновые векторные SVG-иконки, атрибуты доступности (a11y).
* **CSS3**: Кастомные CSS-переменные для динамических тем, Flexbox, Grid Layout, аппаратно ускоренный стеклянный морфизм, плавные CSS-переходы.
* **Vanilla JavaScript (ES6+)**: Управление состоянием видеоплеера, переключение тем, поисковая фильтрация и буфер обмена.
* **Google Fonts**: Современная типографика Onest и Unbounded.

## Быстрый старт

### Локальный запуск
Не требует сборки и веб-серверов. Достаточно открыть файл `index.html` в любом современном браузере:

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Развертывание
Благодаря полной статичности проект моментально разворачивается на любом хостинге:
* **GitHub Pages**: Включите в настройках репозитория (Settings → Pages → ветка `main`).
* **Vercel / Netlify / Cloudflare Pages**: Развертывание в один клик без конфигурации сборки.
* **Любой веб-сервер**: Nginx, Caddy, Apache или локальный `python -m http.server`.

## Сообщество и поддержка

* Официальный Telegram канал разработчика: https://t.me/KreziBro_dev
* Поддержать развитие проекта на платформе Ko-fi: https://ko-fi.com/krejzibro

## Лицензия

Распространяется под лицензией MIT. Подробности в файле [LICENSE](LICENSE).
