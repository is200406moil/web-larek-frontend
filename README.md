# Web-ларёк

Интернет-магазин для веб-разработчиков. Позволяет просматривать каталог, добавлять товары в корзину и оформлять заказы.

[Репозиторий на GitHub](https://github.com/is200406moil/web-larek-frontend)

## Описание

Проект реализован по принципу MVP (Model-View-Presenter):
- **Model** — работа с API, хранение и обработка данных.
- **View** — отображение интерфейса и взаимодействие с пользователем.
- **EventEmitter** — связывает Model и View, реализует паттерн Observer.

### Технологии
- HTML, SCSS, TypeScript
- Webpack

### Структура
- `src/` — исходные файлы
- `src/components/` — компоненты приложения
- `src/pages/index.html` — главная страница
- `src/types/index.ts` — типы
- `src/index.ts` — точка входа
- `src/scss/styles.scss` — стили

### Основные классы
- `Api` — работа с сервером
- `ApiModel` — получение/отправка данных
- `BasketModel` — корзина пользователя
- `DataModel` — хранение данных о товарах
- `FormModel` — хранение и валидация данных форм
- `Basket`, `BasketItem`, `Card`, `CardPreview`, `Order`, `Contacts`, `Modal`, `Success` — отображение и взаимодействие с пользователем

## Установка и запуск

```bash
npm install
npm run start
```
или
```bash
yarn
yarn start
```

## Сборка
```bash
npm run build
```
или
```bash
yarn build
```

## Автор
Исма, 2025
