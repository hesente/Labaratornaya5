# Labaratornaya5

# Лабораторная работа №5: Хранение данных. Настройки и внешние файлы

## Основные функции:
- **Сохранение в SharedPreferences**: Приложение сохраняет данные (заголовок и сообщение) в файл настроек.
- **Загрузка из SharedPreferences**: Данные восстанавливаются и отображаются на экране.
- **Сохранение во внешний файл**: Данные сохраняются в файл, доступный только приложению.
- **Загрузка из внешнего файла**: Данные извлекаются из файла и показываются пользователю.

## Описание
- Android-приложение иллюстрирует использование различных методов хранения данных в мобильных приложениях. Оно позволяет сохранять данные в `SharedPreferences` и работать с внешними файлами для записи и чтения. Основной функционал включает сохранение и загрузку пользовательских данных, таких как заголовок и сообщение.


## Структура приложения:
Приложение состоит из одного экрана с четырьмя основными функциями:

1. **MainActivity**:
   - **Описание**: Экран для ввода данных, их сохранения и загрузки из разных источников.
   - **Кнопки**:
     - **Сохранить в SharedPreferences**: Сохраняет данные в \`SharedPreferences\`.
     - **Загрузить из SharedPreferences**: Загружает данные из \`SharedPreferences\`.
     - **Сохранить в файл**: Сохраняет данные во внешний файл.
     - **Загрузить из файла**: Загружает данные из файла.

2. **Функции для работы с данными**:
   - **saveToSharedPreferences()**: Сохраняет данные в \`SharedPreferences\`.
   - **loadFromSharedPreferences()**: Загружает данные из \`SharedPreferences\`.
   - **saveToFile()**: Сохраняет данные в файл.
   - **loadFromFile()**: Загружает данные из файла.
