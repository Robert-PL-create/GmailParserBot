<img width="338" alt="image" src="https://github.com/user-attachments/assets/6cd9e8ec-156b-4a36-ab4c-39631a15ddca"># GmailParserBot

[![GitHub](https://img.shields.io/badge/GitHub-Repo-blue)](ссылка)

## Команда

- **Пушкин(tg:@roshlght)** - работа с gmail api
- **Казицин** - телеграм бот
- **Храмов** - обработка и анализ писем
- **Щемелев** - работа с базами данных, логи

## Описание

GmailParserBot — это Telegram-бот, который уведомляет пользователей о важных письмах из их Gmail. Пользователь предоставляет боту свои учетные данные (credentials), привязывая свою Gmail почту, и бот начинает уведомлять его о важных письмах. Важность писем можно настраивать по фильтрам или ключевым словам.
Пример работы: https://disk.yandex.ru/i/4tytD-VC-3taWg

## Технологии

В разработке данного проекта использовались следующие технологии и инструменты:

### Фреймворки и библиотеки
- **Flask**
  - Лёгкий веб-фреймворк для создания серверной части приложения, отвечающей за обработку OAuth2 колбэков.

- **python-telegram-bot**
  - Библиотека для взаимодействия с Telegram Bot API, упрощающая создание и управление ботом.

- **google-auth-oauthlib**
  - Библиотека для реализации OAuth 2.0 аутентификации и авторизации с использованием учетных данных Google.

- **google-api-python-client**
  - Библиотека для взаимодействия с различными API Google, включая Gmail API.

- **SQLite**
  - Встроенная база данных для хранения учетных данных пользователей и другой информации.

### Инструменты и сервисы
- **ngrok**
  - Инструмент для создания публичного туннеля к локальному Flask-серверу, необходимого для обработки OAuth2 перенаправлений.

### Дополнительные технологии
- **OAuth 2.0**
  - Протокол аутентификации и авторизации, используемый для безопасного доступа к Gmail API от имени пользователей.

## Использование

1. **Авторизация:**
    - В Telegram отправьте команду `/start` вашему боту.
    - Перейдите по ссылке для авторизации через Gmail и следуйте инструкциям.

2. **Получение писем:**
    - После успешной авторизации отправьте команду `/get_emails` вашему боту для получения последних писем из Gmail.
   
## Как использовать

1. Запустите бота в Telegram.
2. Предоставьте необходимые учетные данные для доступа к вашей Gmail почте.
3. Настройте фильтры для определения важных писем.
4. Получайте уведомления о важных письмах в реальном времени!

(Для тестировщиков: локальны нужны файлы client_secret3.json и apikey (гмэйл апишка и токен тг бота))
