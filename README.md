##final2024bebra
Присвоенное имя робота в сети:
```
turtlebro55
```
IР-адрес робота в сети роутера-полигона:
```
192.168.1.XX
```
Текущая частота подключения робота к сети 5 ГГц:
```
iwconfig
```
Скорость передачи данных через сетевой интерфейс робота(Мбит/с):
```
iperf3 -c 192.168.1.XX
```
Название дистрибутива и кодовое имя сборки Linux:
```
lsb_release -a
```
Версия интерпретатора Python3:
```
python3 -V
```
Версия библиотеки rospy:
```
rosversion rospy
```
Версия библиотеки turtlebro:
```
rosversion turtlebro
```
Версия прошивки микроконтроллера материнской платы и серийный номер системной платы робота:
```
rosservice call /board_info {}
```
Размер оперативной памяти (Мбайт):
```
free -m
```
Текущий часовой пояс на роботе в формате "Time
zone:Continent/City (XXX, +XXXX)":
```
timedatectl|grep "Time zone"
```
Серийный номер Raspberry Pi 4:
```
cat/sys/firmware/devicetree/base/serial-number
```
Топики из инструкции к роботу присутствуют на роботе:
```
rostopic list
```

