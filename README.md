# neto-hw
Задание 1
https://hub.docker.com/repository/docker/felpucci/custom-nginx/general

Задание 2,3,4
приложил скрины

Задание 5
Какой из файлов был запущен и почему?
- был запущен compose.yaml так как он считается дефолтным, а docker-compose.yaml обычно нужен для обратной совместимости с ранними версиями docker compose
Прочитайте warning, объясните суть предупреждения и выполните предложенное действие
-warning напрямую говорит, что нашлись контейнеры-сироты для этого проекта, жмите опцию --удалить-сироту чтоб почистить, если удалили/переименовали этот сервис из компоуз файла:
--remove-orphans            Remove containers for services not defined in the Compose file
