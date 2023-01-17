---
title: "WAN"
date: 2023-01-17T09:13:53-06:00
draft: true
---


# Redes de área amplia

Una WAN abarca una gran área geográfica. País o continente

`ping new` desconecta si hay collisiones en pings

`traceroute` maximo numero de saltos en 30

Lineas de transmisión mueven bits entre máquinas (fibra óptica, cobre)
Lineas de conmutación. Son computadoras que conectan 3 o más líneas de transmisión (i.e conmutadores, switches(lan), routers(wan) y enrutadores)

Redes de computadoras pueden ser de hosts (computadoras) o de conmutadores

## Subred de almacenamiento y envío

+ Store and foward o conmutación de paquetes
+ Casi todas las redes de área amplia tienen subredes de almacenamiento y reenvío

### Desiciones de enrutamiento

se hacen de manera local
si llega a A decide si enviarlo a B o C
algoritmo de enrutamiento

## Interredes

Un conjunto de redes incorconectadas se llama interred.

+ ip
+ Mascara
+ puerta de enlace (gateway) (ataques de seguridad en gateways)

TODO: cambiar DNS de BUAP a  google


## Subredes Redes Interredes

Lan, el cable y host forman una red

Subred tiene más sentido en una compañia subred de directivos, contabilidad, etc.. Muchos equipos separados en fragmentos más pequeños

Interred se forma cuando se interconectan redes diferentes. (varias redes LAN y WAN)

## Software de Redes

Este sf está dividido en capas. Modelo OSI

### protocolo

Acuerdo entre partes sobre cómo comunicarse
<!-- NOTE: inside diapos -->
![MODELO OSI IMAGE](redes/)

## Consideraciones

+ Identificar emisores y receptores
+ Reglas de la transferencia de datos: 
+ Control de errores (circuitos de comunicación física no son perfectos)

## Servicios orientados y no orientados a la conexión

Conexión: el usuario del primer servicio establece una conexión, la utiliza y la abandona.
  TCP
Sin conexión:
  UDP

## Calidad de sevicio

Es confiable si nunca pierde datos
Garantiza que las prioridades coincidan con el tipo de comunicación (e importancia para la organización)

## Sistemas abiertos

Se trata de compatibilidad entre diferentes redes de fabricantes

<!-- TODO: investigar capas de modelo OSIU y descriptción 2 a 3 renglones lo que hace cada capa -->
