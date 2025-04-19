---
sidebar_position: 6
---

# Mostrar detalle de la cita
Como veterinaria necesito ver con mas detalle la informacion de las citas, para tener mejor conocimiento sobre la cita.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario: -->
<!-- ![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para mostrar detalle:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-5-5-1 | Ver mas | Cuando el usuario presione el simbolo de ver mas, se dirigira a una nueva ventana solo con los datos de la cita |
| MVP-5-5-2 | Regresar del ver mas | Cuando el usuario regrese de la pestaña "ver mas" la tabla no se debera de ver afectada por el cambio de ventana. |
| MVP-5-5-3 | Mostrar nombre del tutor | La ventana "ver mas" debera de mostrar el nombre del tutor en minusculas y sin caracteres especiales, si hay tildes, se debera de mostrar el caracter sin tilde. |
| MVP-5-5-4 | Mostrar rut del tutor | La ventana "ver mas" debera de mostrar el rut del tutor con "." y "-", ademas al presionar el rut, redirigira al usuario al perfil del tutor. |
| MVP-5-5-5 | Mostrar nombre de la mascota | La ventana "ver mas" debera de mostrar el nombre de la mascota en minusculas y sin caracteres especiales, si hay tildes, se debera de mostrar el caracter sin tilde. |
| MVP-5-5-6 | Mostrar rut de la mascota | La ventana "ver mas" debera de mostrar el rut de la mascota, ademas al presionar el rut, redirigira al usuario a la ficha de la mascota. |
| MVP-5-5-7 | Mostrar motivo de la cita | La ventana "ver mas" debera de mostrar el motivo de la consulta en un campo de maximo 500 caracteres, siendo visibles todos los anotados para la cita, a su vez, debera de estar en minuscula y sin tildes. |
| MVP-5-5-8 | Mostrar fecha de la cita | La ventana "ver mas" debera de mostrar la fecha de la cita en formato "DD-MM-YYYY". |
| MVP-5-5-9 | Mostrar hora de la cita | La ventana "ver mas" debera de mostrar la hora de la cita en formato "HH:MM". |
| MVP-5-5-10 | Mostrar el monto de la cita | La ventana "ver mas debera de mostrar el motno de la cita con el formato "$xx.xxx". |
| MVP-5-5-10 | Mostrar tipo de urgencia de la cita | La ventana "ver mas" debera de mostrar el tipo de urgencia los cuales pueden ser "Alta", "Media", "Baja". |
| MVP-5-5-11 | Mostrar el id de la cita | La ventana "ver mas" debera de mostrar el id de la cita. |

## Mockaps

### Mostrar detalle de citas sin error
<!-- ![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg) -->

### Mostrar detalle de citas con marca de error
<!-- ![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->