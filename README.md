# 05-virt-03-docker-intro
# Задание 1
https://hub.docker.com/repository/docker/littlelucidlynx/custom-nginx/general

# Задание 2
![Image alt](https://github.com/littlelucidlynx/05-virt-03-docker-intro/raw/main/Screen/Docker001.png)

# Задание 3
![Image alt](https://github.com/littlelucidlynx/05-virt-03-docker-intro/raw/main//Screen/Docker002.png)

Команда Ctrl+C посылает сигнал SIGKILL, который убивает процесс и останавливает контейнер

# Задание 4
![Image alt](https://github.com/littlelucidlynx/05-virt-03-docker-intro/raw/main//Screen/Docker003.png)

Контейнер запущен с пробросом 8080 порта хоста к 80 порту контейнера, который слушает nginx. После изменений изменений nginx слушает порт 81, который с хоста не проброшен

# Задание 5
Compose понимает файлы compose.yaml и docker-compose.yaml. По умолчанию используется файл compose.yaml из текущего расположения. Если присутствуют оба файла, приоритетным является compose.yaml

