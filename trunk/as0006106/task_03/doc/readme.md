Министерство образования Республики Беларусь  
Учреждение образования   
Брестский Государственный Технический Университет  
Кафедра ИИТ
<br/><br/><br/><br/><br/><br/><br/><br/><br/>
## Лабораторная работа №3
## "Работа с контроллером AXCF 2152"
<br/><br/><br/><br/><br/><br/><br/><br/><br/>
Выполнила:  
Студент 3 курса  
Группы АС-61  
Карпович И. В.  

Проверил:
Иванюк Д.С.
<br/><br/><br/><br/><br/><br/><br/><br/><br/>
Брест 2023

### Цель работы: запустить проект на контроллере AXCF 2152
## Ход работы 

Используя визуальный код, создайте тестовый проект «Hello PLCnext from AS06104!», соберите его и продемонстрируйте производительность на тестовом контроллере.

### Шаги для запуска:
1. Клонировать репозиторий «savushkin-rd/PLCnext-howto» на компьютере и собрать исполняемый файл «hello_PLCnext» в Visual Code с помощью CMake.

2. Подключиться к контроллеру через LAN-кабель, предварительно настроив соединение IPV-4. В свойствах этого соединения нам необходимо указать ip-адрес «192.168.1.1» и маску «255.255.255.0».

3. Для проверки соединения используем команду «ping 192.168.1.10» в командной строке, где «192.168.1.10» — ip-адрес контроллера. Если пакеты не теряются, значит соединение установлено правильно.

4. Установите на компьютер 2 программы: PuTTY и WinSCP.

5. С помощью PuTTY подключаемся к контроллеру, введя ip-адрес контроллера, логин - "admin" и пароль - "785*****".

6. Перенести исполняемый файл в корень контроллера с помощью программы WinSCP. Также вводим ip-адрес, логин и пароль контроллера.

7. Изменить права доступа на запуск исполняемого файла.

8. Запустить исполняемый файл.