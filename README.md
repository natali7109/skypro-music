## Skypro.Music — Декомпозиция главной страницы

### ✅ Что сделано:
- Создан Vue-проект с Vite
- Выполнена декомпозиция главной страницы на 5 компонентов:
  - `Navbar.vue` — боковое меню
  - `FilterControls.vue` — поиск и фильтры
  - `Playlist.vue` — список треков
  - `Track.vue` — отдельный трек
  - `PlayerBar.vue` — аудиоплеер

### 📁 Структура проекта:
src/
├── components/
│ ├── Navbar.vue
│ ├── FilterControls.vue
│ ├── Playlist.vue
│ ├── Track.vue
│ └── PlayerBar.vue
├── data/
│ └── tracks.js
├── App.vue
└── main.js

text

### 🎨 Статика:
- Шрифты Montserrat в `public/fonts/`
- Обложки треков в `public/img/cover/`
- Обложки плейлистов в `public/img/playlist/`

### 🎵 Данные:
- Создан `tracks.js` с 5 треками
- Структура: `id, title, artist, duration, date, cover, audio`

### ✅ Критерии выполнены:
- [x] Проект на Vite
- [x] 5 компонентов в `components/`
- [x] Стили инкапсулированы (`scoped`)
- [x] Статика в `public/`
- [x] Файл с треками подключён
- [x] Шрифт Montserrat
- [x] Интерфейс соответствует макету
- [x] Консоль чиста

### 🚀 Запуск:
npm run dev