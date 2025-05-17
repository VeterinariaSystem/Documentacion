---
sidebar_position: 18
---

# Agregar Ficha

Como veterinaria necesito agregar fichas para poder tener datos en mi sistema.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para agregar fichas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-7-1-1 | La ficha debera de tener el nombre de la mascota | El nombre de la mascota, debera de tener como maximo 200 caracteres y como minimo 1 caracter, este campo es obligatorio. |
| MVP-7-1-2 | La ficha podra tener apellido de la mascota | El apellido de la mascota debera de tener como maximo 200 caracteres y como minimo 0 caracter, este campo es opcional. |
| MVP-7-1-3 | La ficha debera de tener un identificador | El formato del identificador unico y debera de contar con minimo 5 caracteres, este campo es obligatorio y se generara automaticamente. |
| MVP-6-1-4 | La ficha debera de tener el tipo de especie | El tipo de especie, sera un listado con los tipos de especies que hay(canino, felino, reptil, ave, rodeor, etc...), este campo es obligatorio. |
| MVP-6-1-5 | La ficha debera de tener la fecha de nacimiento de la mascota | la fecha de nacimiento debera de tener el formato DD-MM-YYYY, este campo es obligatorio. |
| MVP-6-1-6 | La ficha debera de tener la raza de la mascota | EL nombre de la raza, debera de tener maximo 200 caracteres y como minimo 1, este campo es obligatorio. |

| MVP-6-1-7 | La ficha debera de tener el sexo de la mascota | El sexo de la mascota, podra ser "Macho" o "Hembra". |
| MVP-6-1-8 | La ficha debera de tener las enfermedades de la mastora | Las enfermedades de la mascota, deberan de tener como maximo 500 caracteres y como minimo 0, este campo es opcional. |
| MVP-6-1-9 | El tutor debera de tener la opcion de ver con mas detalles | El tutor tendra una opcion que permita ver con mas detalles los datos de este. |
| MVP-6-1-10 | El tutor debera de elegir el pais de residencia | El tutor tendra que seleccionar su pais de residencia de la lista que se le presentara. |


## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->