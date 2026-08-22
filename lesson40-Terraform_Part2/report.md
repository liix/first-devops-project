# Отчет: Terraform - Part2

Файл main.tf с блокировкой в s3

![Скриншот](screenshots/0-main-with-s3-lock.png)

Создание s3

![Скриншот](screenshots/1-s3.png)

Редактирование ACL

![Скриншот](screenshots/2-acl.png)

Создаем статические ключи

![Скриншот](screenshots/3-static-key.png)

Terraform использует s3 для хранения state

![Скриншот](screenshots/4-backet-with-state.png)

Создаем базу

![Скриншот](screenshots/5-managed-service-for-ydb.png)

Копируем api endpoint

![Скриншот](screenshots/6-api-endpoint.png)

Обновляем main.tf для использования бд

![Скриншот](screenshots/7-main-with-lock.png)