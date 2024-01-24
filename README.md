# unmtm_microservices
unmtm microservices repository

Gitlab CI. Построение процесса непрерывной интеграции

Выполнены все основные задания

# Основное задание
В файле `gitlab-ci/docker-compose.yml` описана установка gitlab-ce через `docker compose`;
Запуск через `docker compose up -d` отработал успешно, GitLab поднялся по адресу http://yc-vm-ip/;


# Проект в GitLab
В GitLab созданы группа `homework` и проект `example`;
В файле `.gitlab-ci.yml` описан CI/CD Pipeline;
Установлен и зарегистрирован GitLab Runner;
Пайплайн успешно отработал;
Тесты в пайплайне изменены в соответствии с ДЗ;
Определены окружения `dev`, `beta` и `production`;
Определены окружения `stage` и `production` для выкатывания кода с явно зафиксированной версией (помеченного с помощью тэга в git);
Добавлены динамические окружения для каждой ветки в репозитории, кроме ветки master;

6c40f42f425e   gitlab/gitlab-runner:latest   "/usr/bin/dumb-init …"   19 minutes ago   Up 18 minutes                                                                                                                                 gitlab-runner
badf95bbcd5c   gitlab/gitlab-ce:latest       "/assets/wrapper"        50 minutes ago   Up 50 minutes (unhealthy)   0.0.0.0:80->80/tcp, :::80->80/tcp, 0.0.0.0:443->443/tcp, :::443->443/tcp, 0.0.0.0:2222->22/tcp, :::2222->22/tcp   gitlab_web_1



Docker-2
Был установлен docker на ubuntu
Ознакомился с основными командами docker
Создал инстанс и проиницировал окружение docker
Собрал свой образ и отправил в dockerhub - docker push unmtm/otus-reddit:1.0
Проверить образ можно с помощью docker pull unmtm/otus-reddit:1.0

