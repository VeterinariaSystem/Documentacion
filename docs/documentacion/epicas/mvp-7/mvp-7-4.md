---
sidebar_position: 21
---

# Mostrar Ficha

Como veterinaria necesito mostrar fichas para poder visualizarlas de mejor forma en mi sistema.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para visualizar fichas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-7-4-1 | Mostrar opcion para agregar | El sistema debera de tener una opcion de agregar ficha, este se econtrara fuera de la tabla con los datos de la citas (mvp-7-1). |
| MVP-7-4-2 | Mostrar datos en la tabla | El sistema debera de mostrar los siguientes datos en una tabla: Identificador, Nombre de la mascota,apellido de la mascota, fecha de nacimiento(formato: DD-MM-YYYY), tipo de especie, sexo de la mascota, raza de la mazcota y el ultimo peso registrado(formato decimal con 2 digitos despues de la coma: "xx,xx"). |
| MVP-7-4-3 | Redireccionar al perfil de la mascota | El sistema debera de permitir que al presionar sobre el "identificador" de la ficha, se muetre el perfil de la mascota. |
| MVP-7-4-4 | Volver del perfil de la mascota  | El sistema no debera de realizar actualizaciones cuando se regrese del perfil de la mascota. |
| MVP-7-4-5 | Mostrar accion "Ver mas" | El sistema debera de mostrar la acciones "Ver mas" la cual al ser presionada, redirigira al "mvp-7-5" |
| MVP-7-4-6 | Volver de la accion "Ver mas"  | El sistema no debera de realizar actualizaciones cuando se regrese de la accion "Ver mas". |
| MVP-7-4-7 | Mostrar accion "Modificar" | El sistema debera de mostrar la acciones "Modificar" la cual al ser presionada, redirigira al "mvp-7-2" |
| MVP-7-4-8 | Volver de la accion "Modificar"  | El sistema debera de actualizar la tabla de fichas cuando se regrese de la accion "Modificar" SOLO si se realizaron cambios, en otro caso, no debera de actualizar la tabla de fichas. |
| MVP-7-4-9 | Mostrar accion "Eliminar" | El sistema debera de mostrar la acciones "Eliminar" la cual al ser presionada, redirigira al "mvp-7-3" |
| MVP-7-4-10 | Volver de la accion "Eliminar"  | El sistema debera de actualizar la tabla de fichas cuando se regrese de la accion "Eliminar" SOLO si se realizaron cambios, en otro caso, no debera de actualizar la tabla de fichas. |


## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->