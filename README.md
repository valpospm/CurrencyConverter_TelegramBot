# CurrencyConverter_TelegramBot
Написание Telegram-бота - конвертера валют.
Имя бота в Telegram - @CurrExchBot по адресу:
<a href="https://t.me/CurrExchBot_bot" target="_blank">t.me/CurrExchBot_bot</a>

Бот выполняет следующие команды:

1. При вводе команды /start или /help пользователю выводятся инструкции по применению бота.
2. При вводе команды /values должна выводиться информация о всех доступных валютах в читаемом виде.
3. Принимает от пользователя сообщение в виде <имя валюты цену которой он хочет узнать> <имя валюты в которой надо узнать цену первой валюты> <количество первой валюты> и выводит значение цены первой валюты.
4. При ошибке пользователя (например, введена неправильная или несуществующая валюта или неправильно введено число) бот выводит пользователю текст с указанием типа ошибки.

Данный бот не запущен, необходимо запустить бот со своего устройства (загрузить данный репозиторий на свой компьютер).
Для работы с данным ботом потребуется установка пакетов: requests, json, telebot.
