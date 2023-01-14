---
title: "Intro"
date: 2023-01-09T10:12:49-06:00
draft: true
---

**Objetivo de redes**: intercambiar información y compartir recursos
### Definiciones

+ Conmutación es la **conexión** que realizan los **nodos** en distinitos lugaes y distancias para vincular a dos usuarios de una red de **telecomunicaciones**
    + Permite la descongestion entre losussuarios de la red lo que permite la descongestión

#### Antecedentes

+ La tarea de conmutar las conexiones, al principio, se hacía a mano. 
    + Las operadoras humaanas fueron sustituidas por ingenieros electromecánicos: las *centralitas*
    + Se incorporó a los teléfonos un disco con números para "marcar" el número del destinatario de la llamada.
    + La centralita decodificaba el número para sbaer a cuál no do conectarse
+ Concexiones a larga distancia conectando centrales
![conexion de 2 centrales de centralitas]()

#### Fases de la conmutación

##### Establecimiento de llamada

Cuando se solicita iniciar una conversación, es preciso averiguar si el destinatario está disponible y en caso afirmativo, debe buscarse un camino libre en la red, que incluye conmutadores dentro de las centrales y enlaces entre las mismas

##### Comunicación

Intercambio de información

## Red de computadoas

***Def: Un conjunto de computadoras autónomas interconectadas***

### Estructura de la red

Defina los elementos de comunicación
+ Tres elementos comunes de comunicación
    + El origen del mensaje
    + El canal
    + El destino del mensaje

<!-- TODO: ver guerreros de la red -->
![imgaen](Warrios of the net)

def: Redes de datos o información capaces de transportar diversos tipos de comunicaciones

#### De qué forma se comunican los mensajes

Los datos se envían a través de mensajes

+ Router
+ Switch
+ PAquetes en subelementos
+ Rutas
+ Paquetes deshechos, reenviados (tcp<=> paquete no llega -> ERR)
    + Avisar que un paquete llegó al destino
    + Collisión o el ruter los descartó

+ Puertos (65523 puertos) ![tabla de puertos]()
    + 80: web
    + 25: email
    + 21: FTP
    + 22: ssh
    + 25:

<!-- TODO: investigar que es un firewall -->
### Firewall

+ Añadir una exception a nuestro Firewall en lugar de deshabilitarlo

**Ping de la muerte**:
```
$ ping google.com -T
```
Enviar paquetes indefinidamente

## Quién inventó el internet

### Joseph Carl Robnett Licklider

Ideas modelaron el internet:
+ red global
+ descentralizada 
+ interfaz gráfica
+ libre flujo
**La red intergaláctica de cómputo**

### En medio de la guerra fría (supremacía mundial)

EEUU funda ARPA, misión no militar. Apoyaba a científicos de universidades estadounidenses para evitar que les ganaran los rusos, les daba gran libertad para investigar. Licklider convenció a sus compas de sus ideas importantews. Entonces, Bob Taylor y Ivn Suthrland fundaron ARPAnet. (flujo de red ineficiente)

Paquetes de red: 60s en francia UK, EEUU Leonard Kleinrock, en lugar de flujo ininterrumpido
+ meta información (más información que la original)
  + cabezera (destino) y cola (final y tamaño de paquete)

1982 surge IP. Cómo empaquetar, etiquetar y transmitir la información.

InterNetworking -> InterNet

Permitía
+ email
+ transferencia y busqueda de archivos (FTP & archi) 
+ BBS (juegos en linea de solo texto)
+ Gopher (precursor de la actual web)

1991 Tim Berners Lee, www father. Experimentaba con hypertexto. trabajaba en el CERN -> Internet + web ==> World wide web
