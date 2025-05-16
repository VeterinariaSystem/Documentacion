---
sidebar_position: 11
---

# Agregar Tutor

Como veterinaria necesito agregar tutores para poder visualizarlos en mi sistema.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para agregar tutores:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-6-1-1 | El tutor debera de tener un nombre | El nombre del tutor debe tener como maximo 200 caracteres y como minimo 1 caracter. Este campo es obligatorio. |
| MVP-6-1-2 | El tutor debera de tener apellido | El apellido del tutor debe tener como maximo 200 caracteres y como minimo 1 caracter. Este campo es obligatorio. |
| MVP-6-1-3 | El tutor debera de tener un rut | El formato del rut debe ser "12.345.678-9" en caso de dni, debera de contar con minimo 5 caracteres. Este campo es obligatorio y no se deben aceptar cadenas vacias. |
| MVP-6-1-4 | El tutor debera de tener un correo | El correo del tutor debera de ser validado segun los caracteres, el "@" y el dominio "xxxxxxxxx@xxxxx.xxxx" a su vez se debera enviar correo de confirmacion para validar la existencia del correo. |
| MVP-6-1-5 | El tutor debera de tener numero telefonico | El numero telefonico debera de tener el identificador "+xx" el cual debera de corresponder con el del pais seleccionado, ademas en caso de ser chileno, se validara la cantidad de caracteres numericos ingresados(maximo 9). |
| MVP-6-1-6 | El tutor debera de tener direccion | La direccion debe tener como maximo 300 caracteres y como minimo 1 caracter. Este campo es obligatorio. |
| MVP-6-1-7 | El tutor debera de tener un historial de citas | El tutor debera de tener un registro de todas las citas que haya soliitado. |
| MVP-6-1-8 | El tutor debera de tener una cantidad de mascotas | El tutor debera de tener registrado la cantidad de mascotas que tenga. |
| MVP-6-1-9 | El tutor debera de tener la opcion de ver con mas detalles | El tutor tendra una opcion que permita ver con mas detalles los datos de este. |
| MVP-6-1-10 | El tutor debera dee elegir el pais de residencia | El tutor tendra que seleccionar su pais de residencia de la lista que se le presentara. |


## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->