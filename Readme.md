Не забываем в файле HOSTS добавить:

127.0.0.1 hello.loc



docker-compose up -d

Переходим по адресу (nginx)
http://hello.loc:8080/ 

docker exec -it php bash
docker exec -it mysql bash

docker inspect mysql
mysql -u root -p


пересобрать сборку:
docker-compose up -d --build

Завершаем работу командой:
docker-compose down

Перечислить образы Docker на вашем компьютере
docker image ls --all

Перечислите контейнеры на компьютере с помощью:  
docker container ls --all  
или  
docker ps -a

DOCKER создает две папки дистрибутив для хранения данных:
\WSL $ \доккер-десктоп
\WSL $ \доккер-десктоп-Дата

// phpmyadmin  
http://hello.loc:8081
// Laravel
http://hello.loc:8080

mklink /D J:\_prg\wsl\root \\wsl$\Ubuntu20.04\root\_prj


https://tretyakov.net/post/ustanavlivaem-phpmyadmin-s-pomoshhyu-docker/

