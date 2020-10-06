# Проектирование и разработка распределенных программных систем

Лекции и материалы по курсу распределенных систем в ЧелГУ, группа ПрИ-401.

## Лекции

### Лекция 1. Введение в распределенные системы

[Презентация](https://docs.google.com/presentation/d/1dKzu38tkdH4NswpoA1xSHBgD2CTQ2E-mPTfmwF19GV0/edit?usp=sharing)

**Ссылки**
1. Мартин Клеппман. Высоконагруженные приложения. Программирование, масштабирование, поддержка
2. [Distributed systems for fun and profit](http://book.mixu.net/distsys/)
3. [Страх и ненависть в распределённых системах](https://habr.com/ru/post/322876/)


### Лекция 2. Асинхронное программирование

[Презентация](https://docs.google.com/presentation/d/1rhkH8aMvMeT8BKP66jPAsK6xILwTX-SD_hGHxOZwwxI/edit?usp=sharing)

**Ссылки**
1. [Highload++ для начинающих](http://highload.guide/blog/highload-for-beginners.html)
2. [Анатомия веб-сервиса](http://highload.guide/blog/inside-webserver.html)


### Лекция 3. Модели данных

[Презентация](https://docs.google.com/presentation/d/1kFSOd4dU5wlFysUVzW85R9MLSkXaueEwIpNOqkhw7WM/edit?usp=sharing)

**Ссылки**
1. [NoSQL – коротко о главном](http://highload.guide/blog/NoSQL-quick-facts.html)
2. Мартин Клеппман. Высоконагруженные приложения. Программирование, масштабирование, поддержка. Глава 2


### Лекция 4. Коммуникация приложений

[Презентация](https://docs.google.com/presentation/d/1uculh-tzuiqvp36jI3Do-Ii4oC7PeU1ERTZnZ_jWUlc/edit?usp=sharing)

**Ссылки**
1. Хоп Грегор, Вульф Бобби. Шаблоны интеграции корпоративных приложений
2. Сэм Ньюмен. Создание микросервисов, глава 4

## Практика

### Практика 1. Контейнеризация и Docker

[Презентация](https://docs.google.com/presentation/d/1jhSh3OhNGEcsuPn_a_NQsS6R1bnwO4x_S7JjWACNizk/edit?usp=sharing)

**Задание**
1. Написать  веб-сервер, который принимает HTTP-запрос и отдает ответ «Hello world»
2. Установить Docker
3. Написать Dockerfile и запустить веб-сервер в докер-контейнере так, чтобы к нему можно было обратиться с хост-машины

**Ссылки**
1. [Установка Docker](https://docs.docker.com/get-docker/)
2. [Документация по Docker](https://docs.docker.com/get-started/)
3. [Документация по Dockerfile](https://docs.docker.com/engine/reference/builder/)

### Практика 2. Взаимодействие контейнеров

[Презентация](https://docs.google.com/presentation/d/1VHCKm0d5Qjuivb6XH6Qk7n5rZlbwin_taiLNCn5vk9s/edit?usp=sharing)

**Задание**
1. Дописать приложение, чтобы оно содержало два эндпоинта
  * POST /links — сохраняет ссылку в БД и возвращает ее id
  * GET /links/<id> — отдает ссылку из БД по id
2. Добавить контейнер с PostgreSQL и настроить его взаимодействие с приложением
3. Настроить запуск обоих контейнеров через Docker Compose


**Ссылки**
1. [Postgres по Docker Hub](https://hub.docker.com/_/postgres)
2. [Сеть в Docker](https://docs.docker.com/network/network-tutorial-standalone/)
3. [Volumes в Docker](https://docs.docker.com/storage/volumes/)
4. [Docker Compose](https://docs.docker.com/compose/)
5. [Документация по docker-compose.yml](https://docs.docker.com/compose/compose-file/)
