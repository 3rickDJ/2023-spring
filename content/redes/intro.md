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
