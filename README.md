# Otus.ToDoList - Telegram-бот

ToDoList на библиотеке Telegram.Bot.

## Запуск

1. Создать бота через @BotFather и получить токен.
2. Задать токен в переменной окружения `TELEGRAM_BOT_TOKEN` (в коде токена нет).

Windows (PowerShell):

    $env:TELEGRAM_BOT_TOKEN="123456:ABC..."
    dotnet run --project Otus.ToDoList

Linux / macOS:

    export TELEGRAM_BOT_TOKEN="123456:ABC..."
    dotnet run --project Otus.ToDoList

В Visual Studio / Rider переменную можно указать в настройках запуска проекта (Environment variables).

После запуска в консоли: "Нажмите клавишу A для выхода". Клавиша A останавливает бота, любая другая выводит информацию о боте (GetMe).

## Команды

/start, /help, /info, /addtask, /showtasks, /showalltasks, /completetask, /removetask, /find, /report
