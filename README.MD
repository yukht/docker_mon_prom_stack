**Получение уведомлений в бот**

*Для получения уведомлений добавьте следующие данные telegram в файл docker-compose.yml*

``
TELEGRAM_ADMIN: "XXX"
TELEGRAM_TOKEN: XXX
``

TELEGRAM_ADMIN - id вашего аккаунта, под которым был создан бот
TELEGRAM_TOKEN - токен, полученный при создании бота

**Вам необходимо создать следующие директории для запуска контейнеров**

``
mkdir data grafana
chmod 775 data grafana
``


