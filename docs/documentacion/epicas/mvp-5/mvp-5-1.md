---
sidebar_position: 2
---

# Agregar Cita

Como veterinaria nesesito agregar citas para poder visualizarlas en mi sistema.

En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg)

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para agregar citas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-5-1-1 | La cita debe tener el nombre del tutor | El nombre del tutor debe tener como maximo 200 caracteres y como minimo 1 caracter. Este campo se autocompleta ingresando el rut |
| MVP-5-1-2 | La cita debe incluir el rut del tutor | El formato del rut debe ser "12.345.678-9", o identificador del pais de recidencia. (El nombre del atributo rut, puede cambiar). Este campo es obligatorio y no se deben aceptar cadenas vacias. |
| MVP-5-1-3 | La cita debe tener el motivo de la consulta | El motivo debe tener como maximo 500 caracteres. Este campo es obligatorio y no se deben aceptar cadenas vacias- |
| MVP-5-1-4 | La cita debe tener un estado | Cuando se crea la cita, debe tener como estado "Aceptado" |
| MVP-5-1-5 | La cita debe tener una fecha y hora | Se deben mostrar todos los horarios disponibles (Explicado en gestion de horarios) que tiene la veterinaria. El formato de la fecha sera la siguiente "12/01/2025" -> Y de la hora sera "20:30 hrs.". Este campo es obligatorio y no acepta informacion vacia. |
| MVP-5-1-6 | La cita debe tener un precio | la cita debe permitir agregar el precio. El cual sera un numero donde los "," seran la representacion del decimal. El formato es "$20.000 CLP", se debe representar que tipo de moneda se cancelo. Este campo es obligatorio y no acepta informacion vacia. |
| MVP-5-1-7 | La cita debe tener el nombre de la mascota | El nombre de la mascota debe tener como maximo 200 caracteres y como minimo 1 caracter. Se mostrara una lista desplegable con las mascotas ingresadas al sistema, ademas de permitir escribir el nombre para poder econtrarla mas rapido (Autocomple) |
| MVP-5-1-8 | La cita debe tener el numero ficha de la mascota | El numero de ficha de la mascota debe ser de tipo alfanumerico donde tendra 7 caracteres. El formato es el siguiente "#1F5P6AK". Este campo se mostrara dependiendo de la mascota que se seleccione |
| MVP-5-1-9 | La cita debe tener un ID | El id de la cita se crea de forma automatica y sera un numero | 
| MVP-5-1-10 | En caso de que se ingrese un rut que no exista | Cuando un rut no existe, debera permitirse agregar un tutor ( MVP-6 ) y luego volver a la pantalla para agregar cita pero con los datos del tutor agregado |
| MVP-5-1-11 | En caso de que no se encuentre una mascota | Cuando se requiera escoger una mascota diferente a las ingresadas al sistema, se permitira agregar una mascota ( MVP-6 ) y luego  volver a la pantalla para agregar cita pero con los datos del tutor de la mascota, y ademas los datos de la mascota agregada al sistema |



## Mockaps
![Mockap de Gestionar citas general](/img/gestionar_citas/gestionar_citas_mockap_general.svg)

![Mockap de Gestionar citas tabla](/img/gestionar_citas/gestionar_citas_mockap_tabla.svg)