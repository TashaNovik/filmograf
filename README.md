## 1. Создать приложение на Vite & React ##
Выполните команду для создания проекта.
Замените <имя-вашего-проекта> на желаемое имя папки для вашего приложения (например, my-react-app).
Используя npm:
npm create vite@latest <имя-вашего-проекта> --template react

## 2. Установка Chakra UI и React Hook Form ##
npm install @chakra-ui/react @emotion/react @emotion/styled framer-motion react-hook-form @chakra-ui/icons

@chakra-ui/react: Основная библиотека компонентов Chakra UI.
@emotion/react, @emotion/styled: Необходимы для работы стилей Chakra UI.
framer-motion: Нужен для анимаций Chakra UI.
react-hook-form: Библиотека для управления формами.
@chakra-ui/icons: Библиотека иконок для Chakra UI (пригодятся для часов, звезд и галочек).

## 3. Создать структуры компонентов  ##
src/
├── components/
│   ├── Header.tsx
│   ├── Footer.tsx
│   ├── MovieCard.tsx
│   ├── MovieList.tsx
│   └── GenreFilter.tsx
├── data/
│   └── mockMovies.ts  # Файл с тестовыми данными фильмов
├── App.tsx            # Главный компонент приложения
└── main.tsx           # Точка входа