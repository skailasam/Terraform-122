Создать бесплатный аккаунт в AWS или Azure (на выбор);
Создать Terraform рецепт, который разворачивает 2 виртуальные машины (EC2 / VM). Зона на выбор;
Создать Docker образ на базе nginx, который будет отдавать при старте статическую страницу с приветствием.
- (опционально): добавить динамики на страницу - вывести публичный IP VM / EC2;
Создать Ansible рецепт, который будет разворачивать по одному экземпляру созданного имеджа на обоих инстансах виртуальных машин;
Сервисы должны быть доступны из сети интернет.
Мы хотим увидеть Terraform код, но установка и настройка EC2 / VM предпочтительнее производить с помощью Ansible.
После выполнения задания просьба предоставить код решения в Git. Репозиторий должен содержать README.md файл с описанием порядка установки и тестирования.


docker run -d -p 1111:80 nginx
