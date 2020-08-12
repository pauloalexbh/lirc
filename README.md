# lirc
Código criado por Paulo Campos para testar comunicaçã infravermelho no Raspberry Pi.

Projeto base:
https://www.instructables.com/id/Setup-IR-Remote-Control-Using-LIRC-for-the-Raspber/

----------------------
descomentar as seguintes linhas e alterar as numerações conforme abaixo:

sudo nano /boot/config.txt


:

#Uncomment this to enable the lirc-rpi module

#dtoverlay=lirc-rpi

dtoverlay=gpio-ir,gpio_pin=27

dtoverlay=gpio-ir-tx, gpio_pin=17

:

-----------------------------


## Esquemático:

![Esquematico](/Imagens/Esquematico.jpeg)

## Pinagem do Sensor VS1838b:

![Sensor_IR](/Imagens/Sensor_IR.jpeg)

## Pinagem do Raspberry Pi Zero:

![Pinagem](/Imagens/Pinagem_Zero.jpeg)

## Pinagem do Raspberry Pi:

![Alt Text](https://github.com/pauloalexbh/interfone/blob/master/Imagens/Pinagem_rev_1.png)

Para mais códigos de Paulo Campos acesse:

* https://github.com/pauloalexbh?tab=repositories

* sudo wget -P /home/piDesktop https://github.com/pauloalexbh/InterruptionsDoor/archive/master.zip

* sudo wget -P /home/piDesktop https://github.com/pauloalexbh/lirc/archive/master.zip

* sudo wget -P /home/piDesktop https://github.com/pauloalexbh/GoogleSheets/archive/master.zip

* sudo wget -P /home/piDesktop https://github.com/pauloalexbh/interfone/archive/master.zip
