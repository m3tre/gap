# gap
grafana alertmanager prometheus
grafana будет использовать СУБД postgresql

Запустить, находясь в папке с клонированным данным репозиторием:
docker compose up -d

В браузере посмотреть:
prometheus:
http://<ip_host_or_vm>:9090/
grafana:
http://<ip_host_or_vm>:3000/
логин:пароль по-умолчанию admin:admin
