# Transvestor Cargo Portal Frontend

Фронтенд-приложение для портала Transvestor Cargo Portal, построенное на React, TypeScript и Vite.

## Технологический стек

- **Фреймворк**: React 18
- **Язык программирования**: TypeScript
- **Сборщик**: Vite
- **Стилизация**: Tailwind CSS
- **UI компоненты**: shadcn/ui (Radix UI)
- **Управление состоянием**: React Query
- **Работа с формами**: React Hook Form + Zod
- **Маршрутизация**: React Router
- **HTTP клиент**: Axios

## Требования

- Node.js (v18 или выше)
- npm или bun

## Начало работы

1. Установка зависимостей:
   ```bash
   npm install
   # или
   bun install
   ```

2. Настройка переменных окружения:
   Создайте файл `.env` в корневой директории со следующими переменными:
   ```
   VITE_API_URL=http://localhost:3000
   ```

3. Запуск сервера разработки:
   ```bash
   npm run dev
   # или
   bun run dev
   ```

Приложение будет доступно по адресу `http://localhost:5173` по умолчанию.

## Доступные скрипты

- `npm run dev` - Запуск сервера разработки
- `npm run build` - Сборка для продакшена
- `npm run build:dev` - Сборка для разработки
- `npm run preview` - Предпросмотр продакшен-сборки
- `npm run lint` - Запуск ESLint

## Структура проекта

```
frontend/
├── src/
│   ├── components/    # Переиспользуемые UI компоненты
│   ├── pages/        # Компоненты страниц
│   ├── hooks/        # Пользовательские React хуки
│   ├── services/     # API сервисы
│   ├── types/        # TypeScript типы
│   ├── utils/        # Утилиты
│   └── App.tsx       # Корневой компонент
├── public/           # Статические файлы
└── index.html        # Входной HTML файл
```

## Возможности

- Современный, адаптивный UI с Tailwind CSS
- Типобезопасная разработка с TypeScript
- Библиотека компонентов shadcn/ui
- Валидация форм с React Hook Form и Zod
- Получение данных с React Query
- Клиентская маршрутизация с React Router
- Уведомления с помощью Sonner
- Графики и визуализация данных с Recharts

## Рекомендации по разработке

1. **Структура компонентов**
   - Используйте функциональные компоненты с TypeScript
   - Реализуйте правильную типизацию пропсов
   - Следуйте паттернам компонентов shadcn/ui

2. **Стилизация**
   - Используйте Tailwind CSS для стилей
   - Следуйте дизайн-системе проекта
   - Поддерживайте принципы адаптивного дизайна

3. **Управление состоянием**
   - Используйте React Query для серверного состояния
   - Используйте React хуки для локального состояния
   - Реализуйте корректные состояния загрузки и ошибок

4. **Качество кода**
   - Следуйте правилам ESLint
   - Используйте осмысленные имена компонентов и функций
   - Добавляйте правильные TypeScript типы
   - Документируйте сложную логику

## Разработка

1. Создайте новую ветку для вашей функциональности
2. Внесите изменения
3. Убедитесь, что все тесты проходят
4. Отправьте pull request

## Лицензия

[Ваша лицензия]
