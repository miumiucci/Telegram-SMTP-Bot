Бот для отправки уведомлений на указанный email-адрес.

Для начала работы внесите токен в переменную окружения в папку .env "TELEGRAM_API_TOKEN". Получить этот токен можно создав своего бота через @BotFather.

Принцип работы:

Для запуска бота нужно отправить команду "/start". Бот предложит ввести почту, на которую нужно будет отправить сообщение Нужно ввести текст сообщения. Тема сообщения по умолчанию "Уведомление" После этого бот отправит сообщение на указанный адрес. Если отправка пройдет успешно, бот выведет соответствующее сообщение в чат. Если нет - сообщение об ошибке.