# Таблица стилей и размеров для проекта «Посмотри в окно»

| Элемент / Класс | Свойство | Значение (px) | Примечание |
| :--- | :--- | :--- | :--- |
| **Общие** | | | |
| `body` | `font-family` | "Fira Sans Condensed", sans-serif | |
| `body` | `font-size` | 18px | |
| `body` | `background-color` | #1b1919 | |
| `body` | `color` | #fff | |
| **Лейаут** | | | |
| `.page` | `max-width` | 1200px | Центрирование через margin: auto |
| `.page` | `min-height` | 100vh | |
| `.content` | `display` | flex | |
| `.content` | `gap` | 24px | |
| `.result` | `flex` | 1 | Занимает основное пространство |
| `.content__details` | `width` | 320px | Фиксированная ширина сайдбара |
| **Видео** | | | |
| `.result__video-container` | `width` | 856px | |
| `.result__video-container` | `height` | 482px | Пропорция 16:9 |
| `.result__video-container` | `margin-bottom` | 24px | |
| **Карточки** | | | |
| `.content__list-container` | `height` | 500px | |
| `.content__list-container` | `overflow-y` | auto | |
| `.content__list` | `gap` | 12px | |
| `.content__list-item` | `padding` | 3px | Для обводки фокуса |
| `.content__video-card` | `gap` | 12px | |
| `.content__video-card-thumbnail` | `width` | 160px | |
| `.content__video-card-thumbnail` | `height` | 90px | |
| **Формы** | | | |
| `.search-form` | `gap` | 16px | |
| `.search-form__checkbox-list` | `gap` | 16px | |
| `.search-form__label` | `gap` | 8px | |
| `.search-form__textfield` | `padding` | 8px 12px | |
| **Кнопки** | | | |
| `.button` | `padding` | 8px 24px | |
| `.search-form__submit-button` | `align-self` | flex-end | Прижата вправо |
| `.more-button` | `width` | 100% | На всю ширину контейнера |