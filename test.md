##Создание и настройка виртуальных машин
-----
1. Создадим виртуальные машины в VirtualBox
![]()
2. Настроим сеть сервера





3. Настроим сеть шлюза

4. Настроим сеть клиента
![](screenshots/client_network1.png)
![](screenshots/client_network2.png)
![](screenshots/client_network.png)
## Настройка профилей виртуальных машин
------
1. Настройка профиля сервера
![](server_profile.png)
2. Настройка профиля шлюза
![](gateway_profile.png)
3. Настройка профиля клиента
![](client_profile.png)
## Подключение по ssh
----
1. Установка на всех машинах OpenSSH
![](screenshots/ssh_server.png)
2. Подключение к серверу по ssh
![](screenshots/ssh_connect.png)
## Конфигурация сети сервера
----
1. Редактирование конфига с настройками сети сервера
![](screenshots/server_network.png)
2. Настройка конфига в текстовом редакторе
![](screenshots/server_network2.png)
3. Проверка конфига на ошибки и его применение
![](screenshots/server_network3.png)
4. Вывод на экран настроенных сетевых интерфейсов сервера
![](screenshots/server_network4.png)
## Конфигурация сети шлюза
-----
1. Редактирование конфига с настройками сети шлюза
![](screenshots/gateway_network1.png)
2. Настройка конфига в текстовом редакторе
![](screenshots/gateway_network2.png)
3. Проверка конфига на ошибки и его применение
![](screenshots/gateway_network3.png)
4. Вывод на экран настроенных сетевых интерфейсов шлюза
![](screenshots/gateway_network4.png)
## Конфигурация сети клиента
-----
1. Редактирование конфига с настройками сети клиента
![](screenshots/client_network1.png)
2. Настройка конфига в текстовом редакторе
![](screenshots/client_network2.png)
3. Проверка конфига на ошибки и его применение
![](screenshots/client_network3.png)
4. Вывод на экран настроенных сетевых интерфейсов клиента
## Создание http-сервера
-------
1. Установим на виртуальную машину (сервер) дистрибутив Python
![](screenshots/python1.png)
2. Установим библиотеку FLask
![](screenshots/python3.png)
6. Создадим текстовый файл,содержащий скрипт создания http-сервера на языке Python
![](screenshots/flask.png)
7. Вручную запустим скрипт
![](screenshots/python7.png)
## Создание службы автозапуска
------
1. В папке с сервисами создадим текстовый документ
![](service1.png)
2. Необходимый текст внутри текстового документа
![](service2.png)
3. Включим службу
![](service3.png)
4. Служба не включилась
![](service4.png)
## Настройка маршрута пакетов с помощью iptables
----
1. Настройка пропуска пакетов, имеющих протокол tcp через 5000 порт. Запрет на отправку всех пакетов по умолчанию
![](screenshots/iptables.png)
3. Список всех ограничений iptables
![](screenshots/iptables2.png)
4. Попытка сохранения ограничений iptables
![](screenshots/save_iptables.png)
5. Сохранение настроек iptables в отдельный файл
![](screenshots/save_iptables2.png)



## Настройка сквозного прохода пакетов через шлюз 
------
1. Включение форвардинга пакетов
![](screenshots/probros.png)
2. Настройка автоматического включения путем редактирования файла sysctl.conf
![](screenshots/probros2.png)
## Проверка работоспосоности сервера
-----
1. С помощью команды curl отправим запрос GET на http-сервер
![](proverka.png)

## Проверка пингов без iptables

