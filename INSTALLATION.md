# 🚀 Установка Terra Engine

## Требования

- [HaxeFlixel](https://haxeflixel.com/) окружение (стандарт для движков на базе FNF)
- Git

> ⚠️ Уточни точные версии Haxe / HaxeFlixel / lime, которые использует именно твоя сборка Terra Engine, и впиши их сюда.

## Шаги установки

1. **Склонировать репозиторий**
   ```bash
   git clone https://github.com/your-username/terra-engine.git
   cd terra-engine
   ```

2. **Установить зависимости**
   ```bash
   haxelib install lime
   haxelib install openfl
   haxelib install flixel
   haxelib install flixel-addons
   haxelib install flixel-ui
   ```

3. **Запустить проект**
   ```bash
   lime test windows
   ```
   (замени `windows` на свою платформу: `mac`, `linux`, `hl` и т.д.)

## Первый запуск

После запуска:

1. Зайди в **Settings** — здесь уже настроены переходы и эффекты по умолчанию
2. При желании включи **Developer Mode** через `Settings → Additional`
3. Готово — движок полностью функционален без дополнительной настройки

## Проблемы при установке?

Задай вопрос в [Discord-сообществе движка](https://discord.gg/suUsPhPEQh).
