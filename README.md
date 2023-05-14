# Контейнеризация (семинары)


![picture for containerization](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/containerization.jpg)

## Урок 2. Механизмы контрольных групп

### **Информация о проекте**

Задание 1:
1) запустить контейнер с ubuntu, используя механизм LXC;
2) ограничить контейнер 256 Мб ОЗУ и проверить, что ограничение работает;
3) добавить автозапуск контейнеру, перезагрузить ОС и убедиться, что контейнер действительно запустился самостоятельно;
4) при создании указать файл, куда записывать логи;
5) после перезагрузки проанализировать логи.

Задание 2*: настроить автоматическую маршрутизацию между контейнерами. Адреса можно взять: 10.0.12.0/24 и 10.0.13.0/24.

Задание со звездочкой - повышенной сложности, это нужно учесть при выполнении (но сделать его необходимо).

***ИЛИ***

***создать несколько процессов и вручную распределить их по разным контрольным группам ограничив различные ресурсы как на семинаре.***


**Задание**

* Установим LXC и шаблоны:
```
sudo apt install lxc lxc-templates uidmap
```


![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-14%2022-16-03.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-14%2022-24-19.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-14%2022-43-16.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-14%2022-55-49.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-14%2022-56-42.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-14%2022-57-22.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-14%2023-04-17.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-15%2000-19-37.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-15%2022-22-54.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-15%2022-23-19.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-15%2022-25-10.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-15%2022-34-14.png?raw=true)
![lxc version](https://github.com/Terekhov-A-S/Containerization-Seminar_3/blob/main/source/2023-05-15%2022-34-30.png?raw=true)







*Подготовил студент Geek Brains* [**`Терехов Александр`**](https://gb.ru/users/7696463), containerization-Seminar_2
