# Robot_lab2#

Laboratorio #2 - Robótica Industrial, entradas y salidas..

Nombres: Jhon Nelson Cáceres Leal


El presente repositorio posee el código RAPID, y los videos tanto de simulación realizada en RobotStudio, como el de práctica grabado en el LabSIR con el módulo existente del controlador IRC5.
En esta práctica se desarrolló un código RAPID capaz de utilizar entradas y salidas digitales.
Descripción solución planteada:
Se utilizó una rutina previamente ya establecida y verificada en funcionamiento, para poder modificar su control a través de condicionales y bucles agregados en el main() del código RAPID.

![image](https://user-images.githubusercontent.com/38961990/232258807-1ea0dc32-c641-4e8f-9792-670f8fbd6e7f.png)


Se realizo un bucle while con el objetivo de que una vez se diera ‘play’ al controlador, este se pudiera ejecutar cuantas veces se quisiera, únicamente oprimiendo alguno de los botones determinados. Así mismo, un condicional IF, para que según el botón oprimido, se ejecutara cierta rutina en el robot ABB.
Cabe resaltar que se utilizó dos entradas digitales, una para la escritura de las letras, y otra para el posicionamiento en una ubicación de mantenimiento. Por otro lado, una salida digital, la cual se encendiera únicamente cuando se estuviera escribiendo. 
RobotStudio:

Para llevar a cabo la modificación del código y su verificación a través de la simulación, se crearon dos entradas y una salida digital en RobotStudio para que este atendiera las órdenes indicadas.
Como se puede observar, cuando es presionado el botón número 1, se enciende la lámpara uno; y por el contrario, cuando se presiona el pulsador número 2, se apaga esta lámpara.

![image](https://user-images.githubusercontent.com/38961990/232258814-3f6e343d-4efd-4725-a636-298bc2c48d75.png)

![image](https://user-images.githubusercontent.com/38961990/232258815-a4b6643c-7b26-4c53-a599-811335b521df.png)

###  LabSIR:

Se obtuvo el resultado deseado, debido a que según las señales de entradas ingresadas, el robot ejecutó lo indicado. Sin embargo, se puede observar que el robot no logra escribir correctamente sobre el tablero del piso, pero esto se debe a que previamente hubo una calibración errónea del robot ABB IRC140, específicamente con la articulación número 4, evidenciando una vez más, la importancia de este proceso. 


###  Video de la simulación :

https://user-images.githubusercontent.com/38961990/232258898-511849ef-9918-475a-a583-de83846e2d1f.mp4



###  Descargas :


[VOJ lab2.zip](https://github.com/jhoncale/Robot_lab2/files/11240911/VOJ.lab2.zip)

