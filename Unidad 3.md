Nombre: Emanuel Nuñez Llamas

Actividad 2.1
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


Switch de capa 3
Ademas de conmutar por MAC, puede enrutar usando, la dirreccion IP del paquete y su tabla de rutas y conecta varias redes o VLAN entre si 

Capa 2 frente a capa 3 
La capa 2 lee la MAC, trabaja en una sola res, nececita un router para comunicar redes distintas y cuesta menos 

Reemplaza a un router
No del todo: el router sigue siendo mejor para conectar con el exterior (WAN, Internet) y para funciones como NAT, El switch de capa 3se usa en campus y centros

Fibra Optica que es
Es un cable de vidrio o plastico muy delgado que transmite los datos como pulzos de luz en lugar de señales elctricas 

Fibra monomodo 
Tiene un nucleo muy delgado (Cerca de 9 micras) por donde viajan un solo haz de luz, generando con laser, alcanza decenas de kilometros  

Fibra multimodo
Tiene un nucleo mar grueso (50 a 62.5 micras) por donde viajan varios haces a la vez, generados con LED, sirve para distancias cortas, como dentro de un edificio. 

Transceptores (SFP)
Es un modulo intercambiable que se inserta en el puerto del switch o router y convierte la señal electrica en luz y la luz en señal electrica 

Ventaja de la fibra optica 
ofrece mucho ancho de banda, llega a mayores distancias, es inmune a la interferencia electromagnetica y es mas dificil de intervenir sin ser detectado 

Desventaja de la fibra optica 
Es muy cara 

Donde se usa la fibra optica 
En el bckbone de internet, en los cables submarinos, en los enlaces entre edificios de un campus y en los centros de datos 

UTP frente a fibra optica 
UTP señal electrica, hasta 100m, economico, sensible a la interferencia 
Fibra pulsos de luz 

Direccion MAC
La direccion MAC es el identificador de 48 bits que tiene cada tarjeta de red y que sirve para identificar el origen y el destino de una trama de LAN (capa 2)

Como se escribe la MAC 
se escribe con 12 digitos hexadecimales, El formato cambia segun el sistema: como guiones en windows 

Estructura de la MAC 
los priemeros 12 bits identifican al fabricante y los ultimos 24 bits los asigna el fabricante a cada tarjeta de modo que la direccion es unica 

Para que sirve la MAC 
los switches usan la MAC para deccidir por que puerto reenviar cada trama y construyen su tabla de direccioens aprendiendo la MAC de origen

Unicast, Multicast y Broadcast
Segun a cuantos equipos va dirigido, Unicast a uno, broadcast a todos, y en multicast a un grupo 

Unicast en el switch 
El switch busca MAC de destino en su tabla de direcciones y envia la trama solo por el puerto donde esta ese equipo 
