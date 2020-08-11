# lirc
Código criado por Paulo Campos para testar comunicaçã infravermelho no Raspberry Pi.

Projeto base:
https://www.instructables.com/id/Setup-IR-Remote-Control-Using-LIRC-for-the-Raspber/

----------------------
sudo nano /boot/config.txt
descomentar as seguintes linhas e alterar as numerações conforme abaixo:

:

#Uncomment this to enable the lirc-rpi module

#dtoverlay=lirc-rpi

dtoverlay=gpio-ir,gpio_pin=27

dtoverlay=gpio-ir-tx, gpio_pin=17

:

-----------------------------


## Esquemático:

![Esquematico](/Imagens/Esquematico.jpeg)

## Pinagem do Sensor:

![Sensor_IR](/Imagens/Sensor_IR.jpeg)

## Pinagem do Raspberry Pi Zero:

![Pinagem](/Imagens/Pinagem_Zero.jpeg)

Para mais códigos de Paulo Campos acesse:

* https://github.com/pauloalexbh?tab=repositories

* wget -P Desktop/ https://github.com/pauloalexbh/InterruptionsDoor/archive/master.zip

* wget -P Desktop/ https://github.com/pauloalexbh/lirc/archive/master.zip

* wget -P Desktop/ https://github.com/pauloalexbh/GoogleSheets/archive/master.zip

* wget -P Desktop/ https://github.com/pauloalexbh/interfone/archive/master.zip
