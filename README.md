# Echo Bot Codex

Простой учебный Telegram-бот, который отправляет пользователю копию
полученного сообщения.

## Возможности

- команда `/start` выводит приветствие;
- бот повторяет текстовые сообщения;
- бот копирует изображения, стикеры, GIF и другие сообщения.

## Запуск на Windows

1. Создайте виртуальное окружение:

   ```powershell
   python -m venv .venv
   ```

2. Активируйте его:

   ```powershell
   .\.venv\Scripts\Activate.ps1
   ```

3. Установите зависимости:

   ```powershell
   pip install -r requirements.txt
   ```

4. Скопируйте `.env.example` в `.env` и укажите токен:

   ```env
   TELEGRAM_BOT_TOKEN=токен_вашего_бота
   ```

5. Запустите бота:

   ```powershell
   python bot.py
   ```

Токен Telegram-бота можно получить через
[@BotFather](https://t.me/BotFather).
