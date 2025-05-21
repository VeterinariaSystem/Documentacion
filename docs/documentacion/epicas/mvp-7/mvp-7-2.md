---
sidebar_position: 19
---

# Modificar Ficha

Como veterinaria necesito modificar fichas para poder tener datos actualizados en mi sistema.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para modificar fichas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-7-2-1 | Ficha de mascota en sistema| La ficha de mascota debe estar ingresado en el sistema para poder modificar sus datos |
| MVP-7-2-2 | Mostrar datos de la ficha de mascota | Al presionar la opcion para modificar, se abrira el formulario con los datos de la ficha llenos |
| MVP-7-2-3 | La ficha debera de tener el nombre de la mascota | El nombre de la mascota, debera de tener como maximo 200 caracteres y como minimo 1 caracter, este campo es modificable. |
| MVP-7-2-4 | La ficha podra tener apellido de la mascota | El apellido de la mascota debera de tener como maximo 200 caracteres y como minimo 0 caracter, este campo es modificable. |
| MVP-7-2-5 | La ficha debera de tener un identificador | El formato del identificador unico y debera de contar con minimo 5 caracteres, este campo no es modificable. |
| MVP-7-2-6 | La ficha debera de tener el tipo de especie | El tipo de especie, sera un listado con los tipos de especies que hay(canino, felino, reptil, ave, rodeor, etc...), este campo es modificable. |
| MVP-7-2-7 | La ficha debera de tener la fecha de nacimiento de la mascota | la fecha de nacimiento debera de tener el formato DD-MM-YYYY, este campo es modificable. |
| MVP-7-2-8 | La ficha debera de tener la raza de la mascota | EL nombre de la raza, debera de tener maximo 200 caracteres y como minimo 1, este campo es modificable. |
| MVP-7-2-9 | La ficha debera de tener el sexo de la mascota | El sexo de la mascota, podra ser "Macho" o "Hembra". este campo es modificable |
| MVP-7-2-10 | La ficha debera de tener las enfermedades de la mascota | Las enfermedades de la mascota, deberan de tener como maximo 500 caracteres y como minimo 0, este campo es modificable. |
| MVP-7-2-11 | La ficha debera de tener el peso de la mascota | El peso de la mascota, debera ser decimal con 2 cifras despues de la ",", ejemplo: "xx,xx", este campo es modificable. |
| MVP-7-2-12 | Modificar los datos de la ficha | Al presionar "Modificar", si todos los datos son validos, el sistema actualizara los datos de la ficha con los datos nuevos |


## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->