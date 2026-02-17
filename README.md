<div align="center">

# 🎮 MC Mod Parser

### Удобный поиск и управление модами для Minecraft

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-brightgreen?style=for-the-badge)](https://xvold.github.io/MC-Mod-Parser/)
[![React](https://img.shields.io/badge/React-19.2.3-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-7.2.4-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)

</div>

---

## ✨ Возможности

- 🔍 **Поиск модов** на Modrinth и CurseForge
- 📦 **Управление списком** модов с выбором версий
- 📥 **Импорт модлистов** из различных форматов (JSON, TXT, CSV)
- 💾 **Экспорт списков** для удобного обмена
- 🎯 **Фильтрация** по версии игры и загрузчику (Fabric, Forge, NeoForge, Quilt)
- 🔗 **Прямые ссылки** на скачивание модов
- 🌙 **Темная тема** для комфортной работы

## 🚀 Быстрый старт

### Требования

- Node.js (v18 или выше)
- npm или yarn

### Установка

```bash
npm install
```

### Разработка

```bash
npm run dev
```

Откройте [http://localhost:5173](http://localhost:5173) в браузере.

### Сборка

```bash
npm run build
```

### Предпросмотр продакшн-сборки

```bash
npm run preview
```

### Деплой на GitHub Pages

```bash
npm run deploy
```

Приложение будет автоматически собрано и задеплоено на GitHub Pages.

## 🛠️ Технологии

| Технология | Версия | Описание |
|------------|--------|----------|
| React | 19.2.3 | UI библиотека |
| TypeScript | 5.9.3 | Типизация |
| Vite | 7.2.4 | Сборщик |
| Tailwind CSS | 4.1.17 | Стилизация |
| Lucide React | latest | Иконки |

## 📁 Структура проекта

```
MC-Mod-Parser/
├── src/
│   ├── App.tsx          # Главный компонент приложения
│   ├── api.ts           # API для работы с Modrinth и CurseForge
│   ├── main.tsx         # Точка входа
│   ├── index.css        # Глобальные стили
│   └── utils/
│       └── cn.ts        # Утилиты
├── .github/
│   └── workflows/
│       └── deploy.yml   # GitHub Actions для автодеплоя
├── index.html
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## 🌐 API

Приложение использует официальные API:
- [Modrinth API](https://docs.modrinth.com/) - поиск и получение информации о модах
- [CurseForge API](https://docs.curseforge.com/) - дополнительный источник модов (требуется API ключ)

## 📝 Лицензия

MIT

---

<div align="center">

Сделано с ❤️ для сообщества Minecraft

[🌐 Открыть приложение](https://xvold.github.io/MC-Mod-Parser/) • [🐛 Сообщить об ошибке](https://github.com/xvolD/MC-Mod-Parser/issues)

</div>
