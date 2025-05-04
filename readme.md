# Шаблон проекта на C++ для test-name

Этот шаблон имитирует структуру проектов на C++ из Microsoft Visual Studio: отдельные файлы для объявлений, реализаций и точки входа.

## Структура проекта

- `include/header.h`: Заголовочный файл с объявлениями функций и подключением библиотек.
- `src/source.cpp`: Реализация функций, импортирует `header.h`.
- `src/main.cpp`: Главный файл, импортирует `header.h` и вызывает функции.
- `Makefile`: Для сборки проекта.
- `.gitignore`: Исключает скомпилированные файлы.
- `.github/workflows/ci.yml`: Настройка CI/CD через GitHub Actions.

## Установка

1. Установите `g++`:

   - Ubuntu: `sudo apt install build-essential`
   - Windows: Используйте MinGW или WSL.
   - macOS: `xcode-select --install`

2. Скачайте или клонируйте этот шаблон.

## Сборка и запуск

1. Сборка:

   ```bash
   make
   ```

2. Запуск:

   ```bash
   ./program
   ```

   Вывод: `Сообщение: Тестовый запуск программы`

3. Очистка:

   ```bash
   make clean
   ```

## Расширение

- Добавляйте новые функции в `header.h` (объявления) и `source.cpp` (реализация).
- Подключайте новые файлы в `Makefile`, если нужно.


---
made by [**Floom**](https://github.com/Floom1)