
##Dispositivo de detección de movimiento de bebes
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
**Instrucciones**


El primer paso para construir el dispositivo es realizar un diseño con las partes que se implementaran, para su funcionalidad, y así obtener una base que apoyo para iniciar.
 ![Prototipo](https://github.com/Miner9908/Proyecto-de-Arquitectura/assets/127722005/cccb2fa0-c76e-4aa3-beb2-f251241eeaf9)

Para llegar a un resultado exitoso, se necesita primero tener el Arduino completamente montado, ya con el sensor y lo demás, después agregarle el módulo GSM, que lo que hará será permitir la alerta, la cual es el resultado que se deseó llegar.


![Circuito](https://github.com/Miner9908/Proyecto-de-Arquitectura/assets/127722005/58829a46-136c-4c78-8288-f5b1d4cbdf3f)


Primero se debe acoplar el Arduino con el módulo GSM, luego se debe conectar el pin tierra a la protoboard, igualmente el pin de 5V, después se hace la conexión del sensor, el pin “gnd” se conecta se conecta a la línea donde ubico la tierra del Arduino, el pin “vcc” a la línea de los 5v, y el pin “out” a uno de los pines digitales. Seguidamente se hace la conexión del led; en donde el lado positivo del led se conecta con un cable a uno de los pines digitales del Arduino, luego el lado negativo se conecta a una resistencia, la cual se encuentra conectada a tierra.
El Arduino se conecta a la computadora, se carga el programa, se desconecta y se hace la respectiva conexión con la batería, para alimentar el dispositivo.


