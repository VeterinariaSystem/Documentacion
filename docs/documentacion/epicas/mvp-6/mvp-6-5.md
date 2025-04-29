---
sidebar_position: 15
---

# Mostrar Detalle Tutor

Como veterinaria necesito ver los detalles de los tutores que se encuentran en mi sistema, para ver mas informacion del tutor.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para mostrar tutores:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-5-4-1 | Mostrar opcion para agregar | El sistema debera de tener una opcion de agregar tutores, este se econtrara fuera de la tabla con los datos de la citas (mvp-6-1). |
| MVP-5-4-2 | Mostrar datos en la tabla | El sistema debera de mostrar los siguientes datos en una tabla: identificador, datos del tutor(nombre y rut), motivo, estado, fecha, hora, monto, perfil de la mascota(nombre, rut) y las acciones("ver mas"(mvp-5-5), "Modificar"(mvp-5-3), "Cancelar"(mvp-5-2)). |
| MVP-5-4-2 | Mostrar tutores de las citas  | El sistema debera de mostrar en la tabla el "nombre del tutor" y el "rut del tutor", este ultimo debera de estar con "." y "-". |
| MVP-5-4-3 | Redireccionar al perfil del tutor  | El sistema debera de permitir que al presionar sobre el "rut" del tutor, se muetre el perfil de este. |
| MVP-5-4-4 | Volver del perfil del tutor  | El sistema no debera de realizar actualizaciones cuando se regrese del perfil del tutor. |
| MVP-5-4-5 | Mostrar identificador de las citas  | El sistema debera de mostrar el numero de la cita. |
| MVP-5-4-6 | Mostrar motivo de las citas  | El sistema debera de mostrar el motivo de la cita, se mostrara un maximo de 100 caracteres. |
| MVP-5-4-7 | Mostrar tipo de urgencia de la citas| El sistema debe de mostrar el tipo de urgencia, las cuales pueden ser "Alta", "Media" y "Baja". |
| MVP-5-4-7 | Mostrar estado de las citas  | El sistema debera de mostrar si la cita esta "Aceptada", "Cancelada" o "Pendiente". |
| MVP-5-4-8 | Mostrar fecha de las citas  | El sistema debera de mostrar la fecha de las citas en el formato "DD-MM-YYYY". |
| MVP-5-4-9 | Mostrar hora de las citas  | El sistema debera de mostrar la hora de las citas en el formato "HH:MM". |
| MVP-5-4-10 | Mostrar monto de las citas  | El sistema debera de mostrar la monto de las citas en el formato "$xxx.xxx". |
| MVP-5-4-11 | Mostrar mascota de las citas  | El sistema debera de mostrar en la tabla el "nombre de la mascota" y el "rut de la mascota". |
| MVP-5-4-12 | Redireccionar a la ficha de la mascota | El sistema debera de permitir que al presionar sobre el "rut" de la mascota, se muetre el perfil de este. |
| MVP-5-4-13 | Volver de la ficha de la mascota | El sistema no debera de realizar actualizaciones cuando se regrese de la ficha de la mascota. |
| MVP-5-4-14 | Mostrar accion "Ver mas" | El sistema debera de mostrar la acciones "Ver mas" la cual al ser presionada, redirigira al "mvp-5-5" |
| MVP-5-4-15 | Volver de la accion "Ver mas"  | El sistema no debera de realizar actualizaciones cuando se regrese de la accion "Ver mas". |
| MVP-5-4-16 | Mostrar accion "Modificar" | El sistema debera de mostrar la acciones "Modificar" la cual al ser presionada, redirigira al "mvp-5-3" |
| MVP-5-4-17 | Volver de la accion "Modificar"  | El sistema debera de actualizar las citas cuando se regrese de la accion "Modificar". |
| MVP-5-4-18 | Mostrar accion "Cancelar" | El sistema debera de mostrar la acciones "Cancelar" la cual al ser presionada, redirigira al "mvp-5-2" |
| MVP-5-4-19 | Volver de la accion "Cancelar"  | El sistema debera de actualizar las citas cuando se regrese de la accion "Cancelar". |


## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->