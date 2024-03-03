# neto-hw
Задание 1 \
https://hub.docker.com/repository/docker/felpucci/custom-nginx/general

Задание 2 \
![ex2-pic1](/images/hw-docker-intro-ex2.png) \
Задание 3 \
![ex3-pic1](/images/hw-docker-intro-ex3-1.png)
![ex3-pic2](/images/hw-docker-intro-ex3-2.png)
![ex3-pic3](/images/hw-docker-intro-ex3-3.png)
![ex3-pic4](/images/hw-docker-intro-ex3-4.png)
![ex3-pic5](/images/hw-docker-intro-ex3-5.png)
![ex3-pic6](/images/hw-docker-intro-ex3-6.png)
![ex3-pic7](/images/hw-docker-intro-ex3-7.png)
![ex3-pic8](/images/hw-docker-intro-ex3-8.png) \
Задание 4 \
![ex4](/images/hw-docker-intro-ex4.png) \
Задание 5 \
![ex5-pic1](/images/hw-docker-intro-ex5-1.png)
![ex5-pic2](/images/hw-docker-intro-ex5-2.png)
![ex5-pic3](/images/hw-docker-intro-ex5-3.png)
![ex5-pic4](/images/hw-docker-intro-ex5-4.png)
![ex5-pic5](/images/hw-docker-intro-ex5-5.png)
![ex5-pic6](/images/hw-docker-intro-ex5-6.png)
![ex5-pic7](/images/hw-docker-intro-ex5-7.png)
**Какой из файлов был запущен и почему?** \
был запущен compose.yaml так как он считается дефолтным, а docker-compose.yaml обычно нужен для обратной совместимости с ранними версиями docker compose \
**Прочитайте warning, объясните суть предупреждения и выполните предложенное действие** \
warning напрямую говорит, что нашлись контейнеры-сироты для этого проекта, жмите опцию --удалить-сироту чтоб почистить, если удалили/переименовали этот сервис из компоуз файла:
> --remove-orphans            Remove containers for services not defined in the Compose file
