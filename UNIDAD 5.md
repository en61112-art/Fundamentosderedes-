
### red y host 
Toda direccion tiene dos partes: la parte de la red, igual para todos los equipos del grupo y la parte de host que identifica a cada equipo

### Direcciones publicas 
Las direcciones publicas son unicas en todo internet y la asigna el provedor de servicios 

### Direcciones privadas 
Se usan solo dentro de una red y no se enrutan en internet: 10.0.0.0/8 172.16.0.0/12 y 192.168.0.0/16 para salir a Internet esan NAT
tarea: ejemplos de NAT

### Direcciones especiales 
127.0.0.1 es el loopback y 169.254.0.0/16 es la asignacion automatica cuando falla el DHCP.
0.0.0.0/0 es la ruta predeterminada 

### Direcciones IPv4 
tiene 32 bits escritos en 4 octetos decimales separados por puntos como 192.168.1.10 una parte identifca la red y la otra el host 

### DCHP
El cliente obtiene su configuracion en cuatri pasos, DORA: Discover, Offer, Request, y Acknowledge, El primer mensaje en brodcast.
El servidor entrga IP, mascar, puerta de enlace yDNS.

### Parca se sirve DHCP
Es un sefvicio que asigna direcciones IP automaticamente a los equipos de red 
evita configurar cada equipo a mano y los conflictos por direcciones duplicadas

### Tiempo de concesion 
Las direccion se entrega en prestamo por un tiempo de conexion, no de forma permanente 
El cliente renueva a la mitad del tiempo; en windows, ipconfig/release libera la direccion e ipconfig/renew pide otra

El pool de direcciones 
El servidor reparte direcciones de un pool y entrega con ellas las mascara, la puerta de enlace y el dns
Las direcciones fijas de servidores, impresoras y routes se excluyan del pool, o se reservan por dirrecion MAC.

### Puertos y relevo de DHCP
DHCP usa UDP, el servidor escucha en el puerto 67 y el cliente en 68
El broadcast no cruza routters, un router con ip helper adrres reenvia las solicitudes a un servidor en otra red.




