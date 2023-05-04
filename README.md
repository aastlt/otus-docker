# otus-docker
Создание образа docker


Для создания кастомного образа nginx на базе alpine был использован Dockerfile

При посещенеии сайта nginx отдаёт кастомную страницу

Ссылка на образ:

https://hub.docker.com/repository/docker/aastlt/otus-nginx-alpine/general


Для для запуска контейнера (например на порту 5050), выполнить:

docker run -d -p 5050:80 aastlt/otus-nginx-alpine:0.1

Проверить доступность сайта: http://localhost:5050
