# elk-docker-compose

Çalıştırma komutları.

docker-compose up -d
docker compose down

Fluent-bit ile log'lar toplanır ve tail eklentisi ile parse edilir.
Elasticsearch'e gönderilir.
Kibana ile görselleştirilir.

Test için logs klasöründe test.log dosyası bulunmakta ve kibana'da onuromertunc isimli index oluşmalı.

![image](https://github.com/user-attachments/assets/d7b612b4-e2e0-4e9a-bf10-012ce8117d71)
