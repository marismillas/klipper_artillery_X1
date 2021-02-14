# klipper_artillery_X1
Esta es mi configuracion para klipper con el extrusor BMG wind, bltouch, correas de sinconizacion del los ejes z sin colocar y nozzle de 0.4. 

Como referencia use el repositorio https://github.com/Clank50AE/Clanks-Klipper-Configs asi lo podreis tener de base para las distintas configuraciones de nuestra impresora.

M600 funcionando, una vex cambie el filamento usar RESUME manualmente.

El archivo config.ini es mi configuracion para superslicer.




Espero para quien quiera empezar a usar klipper que le sirva de ayuda.







Descargamos FluiddPi desde este repositorio https://github.com/cadriel/FluiddPI/releases/tag/v.1.6.1 descomprimimos y usamos https://www.balena.io/etcher/ para flashearlo en vuestra sd.

Una vez flasheado tendremos que editar el archivo <code>fluiddpi-wpa-supplicant</code> donde meteremos nuestra red.

Introducimos la sd en la raspberry y la encendemos.

El proximo paso sera conectarnos a ella via ssh por lo que abriremos el shell de windows y tecleamos <code>ssh pi@ip-de-la-raspberry</code> el password por defecto es "raspberry". Una vez dentro cambiais vuestro password, locales y actualizais el sistema, una vez echo le dais a finalizar y reiniciais escribiendo <code>sudo reboot</code>.

Ya solo resta meter la ip de la raspberry en vuestro navegador con lo que se os abrira el fronted de fluiddpi, añadimos los archivos de configuracion y haremos una calibracion de filamento y del PID
