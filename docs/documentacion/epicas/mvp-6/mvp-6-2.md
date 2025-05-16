---
sidebar_position: 12
---

# Modificar Tutor

Como veterinaria necesito modificar tutores para poder tener los datos correctos en mi sistema.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para agregar tutores:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-6-2-1 | Tutor en sistema| El tutor debe estar ingresado en el sistema para poder modificar sus datos |
| MVP-6-2-2 | Mostrar datos del tutor | Al presionar la opcion para modificar, se abrira el formulario con los datos del tutor llenos |
| MVP-6-2-2 | El tutor debera de tener un nombre | El nombre del tutor debe tener como maximo 200 caracteres y como minimo 1 caracter. Este campo es modificable. |
| MVP-6-2-3 | El tutor debera de tener apellido | El apellido del tutor debe tener como maximo 200 caracteres y como minimo 1 caracter. Este campo es modificable. |
| MVP-6-2-4 | El tutor debera de tener un rut | El formato del rut debe ser "12.345.678-9", o identificador del pais de recidencia. (El nombre del atributo rut, puede cambiar). Este campo es modificable y se debe de verificar si el nuevo rut/dni esta ingresado o no en el sistema, solo se podra modificar si no esta ingresado. |
| MVP-6-2-5 | El tutor debera de tener un correo | El correo del tutor debera de ser validado segun los caracteres, el "@" y el dominio "xxxxxxxxx@xxxxx.xxxx". Este campo es modificable, solo si el nuevo correo no esta registrado en el sistema |
| MVP-6-2-6 | El tutor debera de tener numero telefonico | El numero telefonico debera de tener el identificador "+xx" mas los numero correspondietes segun el identificador. Este campo es modificable, solo si el nuevo no esta registrado en el sistema y si teniendo de pais de residencia chile, cuenta con maximo 9 digitos.|
| MVP-6-2-7 | El tutor debera de tener direccion | La direccion debe tener como maximo 300 caracteres y como minimo 1 caracter. Este campo es modificable. |
| MVP-6-2-8 | El tutor debera de tener un historial de citas | El tutor debera de tener un registro de todas las citas que haya soliitado. |
| MVP-6-2-9 | El tutor debera de tener pais de residencia | El tutor tendra que seleccionar su pais de residencia de la lista que se le presentara. Este valor de modificable pero al hacerlo, debera de validar nuevamente su numero telefonico.|
| MVP-6-2-10 | Modificar los datos del tutor | Al presionar "Modificar", si todos los datos son validos, el sistema actualizara los datos del tutor con los datos nuevos |


## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->