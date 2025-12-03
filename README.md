# «ELK»
## Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

<img src = "img/1_1.jpg" width = 100%>

<img src = "img/1_2.jpg" width = 100%>

## Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

<img src = "img/2_1.jpg" width = 100%>

<img src = "img/2_2.jpg" width = 100%>

## Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

<img src = "img/3_1.jpg" width = 100%>

<img src = "img/3_2.jpg" width = 100%>

## Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

<img src = "img/4_1.jpg" width = 100%>

<img src = "img/4_2.jpg" width = 100%>
