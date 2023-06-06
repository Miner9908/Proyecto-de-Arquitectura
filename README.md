
##Dispositivo de vigilacia para bebes
----------------------------------------------------------
**Materiales**
Para realizar este dispositivo es necesario los siguientes materiales: 
- Arduino uno
- Modulo GSM
- Sensor Pir
- Cables macho-hembra y macho-macho 
- Led 
- Bateria de 9V 
- Resistencia 
------------------------------------------------------------------
**Instrucciones de Montaje**


El primer paso para construir el dispositivo es realizar un diseño con las partes que se implementaran, para su funcionalidad, y así obtener una base que apoyo para iniciar.


![P](https://github.com/Miner9908/Proyecto-de-Arquitectura/assets/127722005/0f774cd2-c904-4976-9772-a6f67c2f481b)


Para llegar a un resultado exitoso, se necesita primero tener el Arduino completamente montado, ya con el sensor y lo demás, después agregarle el módulo GSM, que lo que hará será permitir la alerta, la cual es el resultado que se deseó llegar.


![CircuitoN](https://github.com/Miner9908/Proyecto-de-Arquitectura/assets/127722005/dbb2abd5-7ba6-4e43-b499-1e41e95a25b7)



Primero se debe acoplar el Arduino con el módulo GSM, luego se debe conectar el pin tierra a la protoboard, igualmente el pin de 5V, después se hace la conexión del sensor, el pin “gnd” se conecta se conecta a la línea donde ubico la tierra del Arduino, el pin “vcc” a la línea de los 5v, y el pin “out” a uno de los pines digitales. Seguidamente se hace la conexión del led; en donde el lado positivo del led se conecta con un cable a uno de los pines digitales del Arduino, luego el lado negativo se conecta a una resistencia, la cual se encuentra conectada a tierra.
El Arduino se conecta a la computadora, se carga el programa, se desconecta y se hace la respectiva conexión con la batería, para alimentar el dispositivo.

---------------------------------------------------------------------------------------------
**Instrucciones de Uso**


Al tener montado el dispositivo, se ubica en un lugar donde se logre captar el bebé desde una distancia prudente a la zona de riesgo, para que el dispositivo tenga tiempo de realizar la notificación. 
