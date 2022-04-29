После создания проекта и подключения докера, команды привычного джанго выполняется через pre-face:
docker-compose exec web python manage.py createsuperuser
docker-compose down для удаления image's 
docker-compose up -d для запуска контейнера в background моде, для того чтобы не открывать вторую CMD.
