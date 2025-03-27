# 📱 Telegram Channel Manager Bot

## 🇺🇿 O'zbek tilida

### Bot haqida
Ushbu bot kanallarga xabar yuborish va ularni boshqarish uchun yaratilgan.

### Asosiy funksiyalar
- 📢 **Kanal qo'shish**
  - Username orqali qo'shish (@kanal)
  - Kanal ma'lumotlarini ko'rish
  - Bot admin bo'lishi kerak

- 📝 **Xabar yuborish**
  - Matn xabarlar
  - Rasmlar
  - Videolar
  - Caption bilan media

### O'rnatish
1. Botni ishga tushirish:
```bash
npm install
npm start
```

2. Kerakli sozlamalar:
- BOT_TOKEN - @BotFather dan olinadi
- Bot kanalda admin bo'lishi kerak

### Ishlatish
1. /start buyrug'ini yuborish
2. Kanal qo'shish yoki xabar yuborish
3. Bot ko'rsatmalariga amal qilish

### Texnik yordam
- Admin: @YTurayev
- Bot versiyasi: 1.0.0

## 🇷🇺 На русском

### О боте
Бот создан для управления каналами и отправки сообщений.

### Основные функции
- 📢 **Добавление канала**
  - Добавление через username (@канал)
  - Просмотр информации о канале
  - Бот должен быть админом

- 📝 **Отправка сообщений**
  - Текстовые сообщения
  - Фотографии
  - Видео
  - Медиа с подписью

### Установка
1. Запуск бота:
```bash
npm install
npm start
```

2. Необходимые настройки:
- BOT_TOKEN - получить у @BotFather
- Бот должен быть админом в канале

### Использование
1. Отправить команду /start
2. Добавить канал или отправить сообщение
3. Следовать инструкциям бота

### Техническая поддержка
- Админ: @YTurayev
- Версия бота: 1.0.0

## 🇬🇧 In English

### About Bot
This bot is designed for channel management and message sending.

### Main Features
- 📢 **Add Channel**
  - Add via username (@channel)
  - View channel information
  - Bot must be admin

- 📝 **Send Messages**
  - Text messages
  - Photos
  - Videos
  - Media with captions

### Installation
1. Start the bot:
```bash
npm install
npm start
```

2. Required settings:
- BOT_TOKEN - get from @BotFather
- Bot must be admin in channel

### Usage
1. Send /start command
2. Add channel or send message
3. Follow bot instructions

### Technical Support
- Admin: @YTurayev
- Bot version: 1.0.0

## 🔒 Xavfsizlik / Безопасность / Security

- Rate limiting (5 requests per minute)
- Cache system (1 hour)
- Error handling
- Admin rights required

## 📦 Package.json

```json
{
  "name": "telegram_channel_manager_bot",
  "version": "1.0.0",
  "main": "bot.js",
  "scripts": {
    "start": "node bot.js",
    "dev": "nodemon bot.js"
  },
  "dependencies": {
    "dotenv": "^16.4.1",
    "telegraf": "^4.16.3"
  }
}
```

## 🔑 .env

```env
BOT_TOKEN=your_bot_token_here
```

## 📝 Litsenziya / Лицензия / License
MIT License 
