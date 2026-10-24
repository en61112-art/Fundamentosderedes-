Nombre: Emanuel Nuñez Llamas

Campo 1
Dato de ejemplo: 10101010 10101010 10101010 10101010 10101010 10101010 10101010 10101011 (8 bytes)
Nombre del campo: el preambulo
Para qué sirve: s un mecanismo de calentamiento y sincronización para que ninguna computadora empiece a leer un mensaje a destiempo y la información no se corrompa.

Campo 2
Dato de ejemplo: FFFF.FFFF.FFFF (6 bytes)
Nombre del campo: dirección MAC del broadcast
Para qué sirve: es la dirección universal que garantiza que un paquete sea escuchado por absolutamente todos los dispositivos conectados a tu misma red local

Campo 3
Dato de ejemplo: 0001.4321.ABCD (6 bytes)
Nombre del campo: dirección MAC unicast
Para qué sirve: sirve como la dirección postal exacta para que los datos lleguen directamente a un dispositivo específico y a nadie más

Campo 4
Dato de ejemplo: 0x0806 (2 bytes)
Nombre del campo: etherType
Para qué sirve: sirve como un clasificador rápido de correspondencia, permitiéndole al receptor saber cómo debe interpretar el mensaje antes de empezar a leerlo por completo

Campo 5
Dato de ejemplo: ¿Quién tiene la IP 192.168.1.2? Responde a 192.168.1.1 (entre 46 y 1500 bytes)
Nombre del campo: Payload
Para qué sirve: es el contenido útil de la comunicación, el mensaje real donde una computadora le pide ayuda a la red para asociar una IP con una dirección física

Campo 6
Dato de ejemplo: 0x3A7F91C2 (4 bytes)
Nombre del campo: secuencia de verificación de trama
Para qué sirve: sirve como un control de calidad automático que garantiza que la información recibida sea una copia exacta y fiel de lo que se envió


