---
title: "Pointers"
date: 2023-01-16T14:10:30-06:00
draft: true
---

# Los apuntadores

## Definición: un apuntador es una **variable** que contiene la **dirección** de memoria de una variable
operaciones: suma

```
(int * ) p;
        nombre de la variable
tipo de la variable
```
## Utilización de los apuntadores

Analicemos una porción del siguiente programa
```c
main(){
    int i, j *p; /* p es un apuntador a un entero */
    i = 5;
    p = &i; /* p contiene ahora la dirección de memoria de i */
    j = *p; /* poner en j el contenido de la variable a la que apunta p */
    *p = j + 2;
}
```
