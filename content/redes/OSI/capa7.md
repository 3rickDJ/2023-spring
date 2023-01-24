---
---
# Capas

## PDU

Protocol Data Unit

Capa de aplicación
Tiene todas las funciones y servicios para que el usuario pueda hacer uso de ellas. API

## Capa 7 app 
**Datos**

### Protocolos:

#### Generales

+ DNS: resolver nombres de internet en direcciones ip
+ Telnet
+ BOOTP: obtener una direccion ip

+ DHCP (dinamic host configuration): asignar ip, mascara subred, gateway y servidor DNS a un host
+ http
+ FTP: 21 datos, 20 protocolo, 69 :TFTO:

#### Enviar correo

+ ssh (los protocolos realizan distintas tareas relacionadas con la capa en la que se encuentran)
+ SMTP
+ POP
+ IMAP




### Ataques

DDOS

## Capa Presentación

**Datos**

8822 ISO define los servicios y protocolo de la cap de presentaicón
semántica sintaxis de los datos transmitidos

### Estándares

PICT
TIFF
J

### Funciones

1. Formateo
1. Cifrado
1. Comprensión de datos

## Capa sesión

**Maneja datos**

Administra, establece y finaliza la sesión

### Control del dialogo

Comunicación simultánea de dis vías full-duplex o alternada de dos vías half-duplex

### Protocolos

RPC
SCP
SSH

## Capa 4 Transporte

**Segmentos**

Divide datos (segmentación)

Agrega encabezado(puerto origen y puerto destino)
Poder reensamblar el paquete

+ Asegura que lleguen los datos, completos y correctos

### Protocolos

#### TCP / IP

TCP más lento, pues comprueba la llegada de los mensajes
IP no confirma -> más rápido

#### UDP

En redes locales, no hay aseguramiento de que se haya recivido un paquete 
