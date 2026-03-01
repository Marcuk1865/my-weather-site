# 🌤️ Weather App (Vite + OpenWeather)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

## 🔗 [ОТКРЫТЬ САЙТ](https://marcuk1865.github.io/my-weather-site/)

![Превью сайта](./screen.png)

Простое и быстрое приложение для проверки погоды в любом городе мира.

### 🛠 Стек технологий
* **Инструменты сборки:** [Vite](https://vitejs.dev) — для быстрой разработки и оптимизации проекта.
* **Язык:** JavaScript (ES6+) — использование `async/await`, деструктуризации и стрелочных функций.
* **Работа с данными:** [Fetch API](https://developer.mozilla.org) — для асинхронных запросов к серверу.
* **Геопозиция:** [OpenWeather Geocoding API](https://openweathermap.org) — для конвертации названий городов в координаты и исправления опечаток.
* **Верстка:** CSS3 — использование **Flexbox** для центрирования и **Media Queries** для полной адаптивности под мобильные устройства.
* **Хостинг:** GitHub Pages — автоматический деплой через ветку `gh-pages`.

### ✨ Основные функции
- Поиск погоды по названию города.
- **Умный поиск:** автоматическое исправление опечаток через Geocoding API.
- Отображение температуры (мин/макс), влажности, давления и ветра.
- Адаптивный дизайн для мобильных устройств.

  ### 📈 В планах (Roadmap)
- [ ] Определение местоположения пользователя по кнопке.
- [ ] Смена фонового изображения в зависимости от погоды.
- [ ] Прогноз на следующие 3-5 дней.
- [ ] Локальное хранение последнего запрошенного города (localStorage).


### 🚀 Как запустить локально
1. Клонировать репозиторий: `git clone https://marcuk1865.github.io/my-weather-site/`
2. Установить зависимости: `npm install`
3. Запустить проект: `npm run dev`
