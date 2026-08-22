# Отчет: Terraform - Part3

Пустой main.tf

![Скриншот](screenshots/1-main-start.png)

Создаем сеть и подсеть

![Скриншот](screenshots/2-net-and-subnet.png)

Создаем виртуалку

![Скриншот](screenshots/3-vm.png)

Состояние main.tf перед импортом

![Скриншот](screenshots/4-main-before-import.png)

Импортируем ресурсы

![Скриншот](screenshots/5-import-resources.png)

Ресурсы появились в state

![Скриншот](screenshots/6-state.png)

Копируем поля из состояния в файл main.tf

![Скриншот](screenshots/7-copy-from-state.png)

План показывает, что всё в порядке

![Скриншот](screenshots/8-plan.png)

terraform apply

![Скриншот](screenshots/9-apply.png)

Проверяем, что всё в порядке

![Скриншот](screenshots/10-everything-ok.png)