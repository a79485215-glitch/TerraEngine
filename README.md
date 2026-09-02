<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,6,12,20&height=220&section=header&text=Terra%20Engine&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Движок%20для%20Friday%20Night%20Funkin'&descAlignY=55&descSize=20" width="100%"/>

[<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&letterSpacing=Base&duration=1000&pause=1000000&color=9280F7&background=77FFCC00&center=true&multiline=true&repeat=false&random=true&width=435&lines=%E2%9A%99%EF%B8%8F+%D0%9B%D1%83%D1%87%D1%88%D0%B8%D0%B9+%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82+%D0%B4%D0%BB%D1%8F+%D1%82%D0%B5%D0%B1%D1%8F+%F0%9F%AA%9B" alt="Typing SVG" /></a>](https://readme-typing-svg.demolab.com/demo/?letterSpacing=Base&duration=1000&pause=1000000&color=9280F7&background=77FFCC00&center=true&vCenter=true&multiline=true&repeat=false&random=true&lines=%E2%9A%99%EF%B8%8F+%D0%9B%D1%83%D1%87%D1%88%D0%B8%D0%B9+%D0%B2%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82+%D0%B4%D0%BB%D1%8F+%D1%82%D0%B5%D0%B1%D1%8F+%5E-%5E+%F0%9F%AA%9B+)



![Version](https://img.shields.io/badge/version-v0.1%20BETA-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/status-in%20development-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![FNF](https://img.shields.io/badge/Friday%20Night%20Funkin'-Engine-red?style=for-the-badge)

[![Discord Engine](https://img.shields.io/discord/000000000000000000?color=5865F2&label=Discord%20—%20Сообщество%20движка&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/nwz3UuZxtC)
[![Discord Chat](https://img.shields.io/discord/000000000000000000?color=5865F2&label=Discord%20—%20Общение&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/QYYcDqezRZ)
[![YouTube](https://img.shields.io/badge/YouTube-Terra%20Engine%20FNF-red?logo=youtube&logoColor=white&style=for-the-badge)](https://www.youtube.com/@TerraEngineFNF)

</div>

---

## 📌 О проекте

**Terra Engine** — это движок для *Friday Night Funkin'*, созданный не «с нуля», а как **готовое решение из коробки**.

Идея простая: тебе не нужно разбираться в кодинге, чтении шейдеров или анимационных стейтах, чтобы сделать красивый мод. Всё уже настроено, всё уже работает — остаётся только зайти в **настройки** и подкрутить под себя.

> 💡 Если ты новичок в моддинге FNF — это твой движок.
> 💡 Если ты опытный разработчик — Terra Engine даёт тебе гибкую базу с продвинутой системой эффектов, которую можно расширять.

---

## ✨ Ключевые фишки

| Фича | Описание |
|---|---|
| 🎬 **20+ переходов** | Готовые заготовки переходов между экранами, каждый настраивается отдельно |
| ⏱ **Гибкая длительность** | Duration от `0.5s` до `3s` для каждого перехода |
| 🎛 **Поведение меню** | Zoom по BPM, Zoom с гличом, Zoom с поворотом камеры и другие режимы |
| 🌀 **25+ эффектов на экран** | Отдельные наборы эффектов для FreePlay, Credits, Settings, Story Mode |
| 🛠 **Режим разработчика** | Полноценная встроенная панель редактирования без внешних тулз |
| 📊 **Chart-настройки** | Эффекты музыки, переходы персонажей, поведение летящих стрелок |
| 🧍 **Character Settings** | Настройка анимаций, размеров и скорости анимаций персонажей |
| 🏟 **Stage Editor** | Классический редактор сцен и слоёв |
| 🗂 **Menu Layout** | Полная кастомизация внешнего вида и поведения главного меню |

Подробнее — в [docs/FEATURES.md](docs/FEATURES.md).

---

## 🚀 Быстрый старт

```bash
# Склонировать репозиторий
git clone https://github.com/your-username/terra-engine.git

# Перейти в папку проекта
cd terra-engine

# Открыть в HaxeFlixel / стандартном для FNF-движков окружении
# (см. подробную инструкцию в docs/INSTALLATION.md)
```

Пошаговая установка — [docs/INSTALLATION.md](docs/INSTALLATION.md)

---

## 🧩 Режим разработчика

Terra Engine включает встроенный **Developer Mode** — не нужно лезть в код, чтобы настроить мод.

1. Зайди в **Settings → Additional**
2. Включи галочку **Developer Mode**
3. В главном меню нажми клавишу **`7`**
4. Откроется меню с 4 разделами: **Chart**, **Character Settings**, **Stage Editor**, **Menu Layout**

Подробное описание каждого раздела — [docs/DEVELOPER_MODE.md](docs/DEVELOPER_MODE.md)

---

## 🎨 Переходы и эффекты меню

Полный список из 20+ переходов, режимов поведения меню (Zoom / Zoom+Glitch / Zoom+Camera Rotation) и 25+ эффектов на экранах FreePlay / Credits / Settings / Story Mode описан отдельно:

📄 [docs/MENU_SETTINGS.md](docs/MENU_SETTINGS.md)

---

## 📂 Структура репозитория

```
terra-engine/
├── README.md                 ← ты здесь
├── CHANGELOG.md               ← история версий
├── CONTRIBUTING.md            ← как помочь проекту
├── LICENSE
└── docs/
    ├── FEATURES.md            ← подробный список фич
    ├── INSTALLATION.md        ← установка и запуск
    ├── DEVELOPER_MODE.md      ← режим разработчика (Chart / Character / Stage / Menu Layout)
    └── MENU_SETTINGS.md       ← переходы, zoom-режимы, эффекты экранов
```

## 🤝 Сообщество

| Ссылка | Описание |
|---|---|
| 💬 [Discord — Сообщество движка](https://discord.gg/nwz3UuZxtC) | Новости, обновления, поддержка по движку |
| 💬 [Discord — Общение](https://discord.gg/mNYx7h8QMG) | Общий чат сообщества |
| 📺 [YouTube — Terra Engine FNF](https://www.youtube.com/@TerraEngineFNF) | Обзоры фич, туториалы, тизеры новых версий |

---

## 📜 Лицензия

Проект распространяется по лицензии [MIT](LICENSE) — свободно используй, модифицируй и распространяй с указанием авторства.

---

<div align="center">

**Terra Engine v0.1 BETA** — сделано с 💙 для сообщества Friday Night Funkin'

![Snake animation](https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake.svg)
<br><sub>👆 это пример-заглушка змейки из истории коммитов — своя генерируется через GitHub Action <a href="https://github.com/Platane/snk">Platane/snk</a>, см. примечание ниже</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,12,6,2,0&height=180&section=footer&animation=fadeIn" width="100%"/>

</div>
