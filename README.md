# ELK

### Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

![image](https://github.com/AnastasiyaEvsseva/ELK/assets/151757353/d3720141-099e-42e8-ab42-bb5fe680e1e9)

### Задание 2. Kibana
Установите и запустите Kibana.
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

![image](https://github.com/AnastasiyaEvsseva/ELK/assets/151757353/be644be1-578c-49b7-add2-6acbe494bbc4)


### Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

![image](https://github.com/AnastasiyaEvsseva/ELK/assets/151757353/d16ba050-adbe-4578-a874-e8ffa4de7313)

### Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.

![image](https://github.com/AnastasiyaEvsseva/ELK/assets/151757353/a14f79f5-7614-4f96-8e79-fd669731bb40)






