# Jenkins

Практика по Jenkins.

Задача 1 (file:deploy-docker-apache):
- Создание Dockerfile (ubuntu 16.04, Apache)
- Создание index.html
- Копирование Dockerfile и index.html на вирутальную машину VM-TEST
- Создание Docker image из Dockerfile
- Запуск теста для проверки index.html
- Копирование index.html в Docker контейнер
- Проверка работоспособности в браузере


Задача 2 (file:deploy-git-docker-apache)
- Логин в GitHub
- Клонирование репозитория через SSH на вирутальную машину VM-PROD
- Запуск теста для проверки index.html
- Создание Docker image из Dockerfile
- Копирование index.html в Docker контейнер
- Проверка работоспособности в браузере


Задача 3 (file:deploy-git-ansible-vm)
- Логин в GitHub
- Клонирование репозитория через SSH на вирутальную машину VM-JENKINS
- Установка yamllint
- Запуск теста для проверки разметки YAML в install-nginx.yml
- Запуск файла install-nginx.yml в ansible-playbook
- Копирование index.html в Nginx в папку WWW
- Проверка работоспособности в браузере
