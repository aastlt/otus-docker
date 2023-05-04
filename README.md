# otus-docker


Для создания кастомного образа nginx на базе alpine был использован Dockerfile

При посещенеии сайта nginx отдаёт кастомную страницу

Ссылка на образ:

https://hub.docker.com/r/aastlt/otus-nginx-alpine


Для для запуска контейнера (например на порту 5050), выполнить:

docker run -d -p 5050:80 aastlt/otus-nginx-alpine:0.1

Проверить доступность сайта: http://localhost:5050
