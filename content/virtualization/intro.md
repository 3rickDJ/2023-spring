---
title: "Intro"
date: 2023-01-10T10:13:03-06:00
draft: true
---

# Virtualization y kubernetes

## Virtualization
VM
maquina virtual. 
Cuidado cuando corras una arquitectura diferente a la que uno tiene en docker.
Eligir bien una arquitectura. Seguir con esa misma arquitectura

## Contenedores

- Diferencias:
    + El hypervisor

+ Una app un conteneddor
    + Se pueden comunicar
+ Todo lo de un contenedor debe estar aislado
+ Debe de ser contenerizado, si entras a él, algo estás hacinedo mal

Docker y Podman

![Docker hub](https://hub.docker.com/search?q=)

## BPricesadores
Ek banco de registros, espacio fisico con cabida de siwtches. Cambio a lo largo del tiempo. 8081, vs pentium. La forma en la que modifican el banco de registros. 

Comprar un arduino
Un arduino no es una computadora, hacer paralerlización con arduimo

### Apple 

Cerrado de principio a fin, Sin decisión, sin poder de cambiar

reTocamiento de fotos, circuiteria de software a harfware

#### ARM (muchos nucleos)

## Procesadores
+ SMC
+ Arduino
+ Motorola (lavvadoras
+ Apple

## ROdas las arquitectuars
Bon Newman
Turing

Una vez construida una imagen se vuelve un contenedor

docker run 0d 00name nginx1 0p 80:80 nginx

Se puede restingir un contenedor?

Vagrant - Ambientes de desarrollo sin sistema o;erativo (sin afectarlo)

Los contenedores surgieron a partir con cosas de java

Si necesitas 2 app con java => Empezaron a conteneriza

### kubernetes

Es mala practica. Sila app no puede escala por si misma, un parche (forma facil de solucionar eso) es usar kubernetes.

Master 
Nodos + Nodos + Nodos

Elixir o ruby no hay que contenerizarlo. No es necesario.

Se comen los proocesadores que se quieran

Del contenedor tu puedes ver hacia el mundo. No exponer los puertos.

Puertos

Hacerlo con rails y postgresql

## CI and CD
+ CI (capacidad de decidir que entregar)
    Plan
    Code
    Build
+ Continuos deployment (sacar todo continuamente) 
vs 
+ continuos delivery (cosas que hasta aquí vamos a desplegar, un plan, una capacidad estratégica de decidir algo (basado en pruebas operaciones,))
    Capacidad de quitar con el control de versiones (delivery decisión, deployment decisión)
    Si meto un feat, meto un chat, con Continuos deployment (agregar infraestructura). Continuos delivery (elegir, operar monitorearlo y operarlo)
    Esto es independiente mente de la organización:

Flujo de trabajo y control: Proceso de desarrollo de software

Escenarios: 
+ negocio calro, equipo certero. Un solo branch todo pa arriba.
+ negocio no sabe que quiere | devs muy variados (no desarrollar, negocio, vcs, tec pero no negocio)
    Git flow
    Feat ranch 
    PR

practica de xp, continuos integration vs continuos deployment and delivery

delivery modularizacion del trabajo

c delivery: decisión
c deployment: automatizacion

+ CD (capacidad de poder pesplegar sin meter mano)
    Test
    Release
    Deploy
    Operate

El codigo se integre, se construya y se comprueba continuamente, se va integrando. Push en un repo, baja codigo, se ejecutan pruebas, validaciones de calidad cumplidas. Covertura de código (análisis estático de código, posibilidad de que el codigo tenga un bug, le das reglas para decirle que no permitas métodos con más parámetros), linters

Por qué continuos?
Es automatizadamente y continuamente. 

Todo ya tiene CI y CD

+ Bitbucket
    bitbucket-pipelines.yml
cada que se sube un feat a una rama, o hasta un pR, o hasta una mezcla en rama. 
La mayoria de los casos, cuando pusheas a un repo
 se jecutan los linters, tests, u demas,

Pruebas de unidad: un componente asilado (Aoc)
Pruebas de integración: pruebas todo un feature (agarras un componente que depende de otro, clase A, para clase A deben instanciar clase B dentro de la clase A)(si se necesita instancia otro componente es prueba de integración) (con bases de datos)
Pruebas funcionales: dado algo, sale algo (prueba de endpoint(de punta a punta), llamada a processos y todo )

Tan complejo o simple como se quiera. Con un Jenkis.

Pueden estar  atados o ser manuales. CUando termine de pasar un test de integración.
TODO: como ejecutar un deployment al pushear un tag a GitHub , con GitHub actions
Deployment: puede ser desde un simple shell script hasta una herramienta de automatización completa OOOOooooooo
ANSIBLE es una heramienta que hace códigos de forma automzatizada y organizada. En lugar de tener un solo shell script. En ansible tenemos roles (ejecución de n cosas). En este caso la cada rol es la ejecución de una aplicación. Ejecución de roles se ejecuta main.yml



Herramienta como Jenkis, travis, (Bitbucket, github actions, redis(complicado) )

+ GitHub
+ GitLab


Orientación de obketos, 
<!-- parametrización de objetos -->

Terminar codebreaker

pdf, epub, html, psuh a repo

Repetir string calculatpor con cucumber
Reemplazar los feat given when then con selenium-cucumber
