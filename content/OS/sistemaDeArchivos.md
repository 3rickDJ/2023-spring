---
title: "Pointers"
date: 2023-01-16T14:10:30-06:00
draft: true
---

# Sistema de archivos

## Características de un Sistema de archivos

Un sistema de archivos es un mecanismo de abstracción de los dispositivos físicos de almacenamiento, que nos permite manejarlos a un nivel lógico, sin necesidad de conocer su arquitectura hardware

Características:
+ Posee una estructura jerárquica
+ Realiza un tratamiento consistente de los datos de los archivos
+ Puede crear y borrar archivos
+ Permite un crecimiento dinámico de los archivos
+ Proteje los datos dinámicos de los archivos
+ Trata los dispositivos y periféricos terminales, unidades de cinta, discos, etc.., como si fueran archivos.

## Estuctura del sistema de archivos

+ Secuencia de bloques lógicos, cada uno de los cuales tiene un tamaño fijo
+ El tamaño del bloque es el mismo para todo el sistema de archivos y suelen ser multiplos de 512 bytes

| bloques de boot | Superbloque         | lista de nodos-i            | bloque de datos |
| ---             | ---                 | ---                         | ---             |
| daemons         | carga los metadatos | informacion de los archivos |                  |

Disco duro se divide en bloques de 512 bytes. Particionado por bloques -> Superbloque ->  I-Nodo (con metadato (dato de dato))
