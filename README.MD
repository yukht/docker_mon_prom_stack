***Получение уведомлений в бот***

*Для получения уведомлений добавьте следующие данные telegram в файл docker-compose.yml*

``TELEGRAM_ADMIN: "XXX"``

``TELEGRAM_TOKEN: XXX``

TELEGRAM_ADMIN - id вашего аккаунта, под которым был создан бот

TELEGRAM_TOKEN - токен, полученный при создании бота

***Необходимо создать следующие директории для запуска контейнеров***

``mkdir data grafana alertmanager/data``

``chmod 775 data grafana``

``chmod 777 alertmanager/data``

***Grafana***

Для добавления datasource Prometheus указывайте в Grafana имя контейнера

``http://prometheus:9090``

Для ознакомления с возможностями Grafana по визуализации значений метрик можно скачать готовые дашборды (устанавливаются через Dashboards -> Import)

*grafana node exporter dashboard*

*grafana blackbox dashboard*
