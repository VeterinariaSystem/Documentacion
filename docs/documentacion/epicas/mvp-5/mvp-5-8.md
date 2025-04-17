---
sidebar_position: 9
---

# Buscar citas
Como veterinaria necesito buscar las citas en mi sistema para acceder a ellas con mayor facilidad.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario: -->
<!-- ![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para buscar citas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-5-9-1 | Autorizacion de busqueda | El sistema permitira realizar la busqueda de citas SOLO a la veterinaria |
| MVP-5-9-2 | Limitar caracteres en el buscador | El buscador de citas, tendra un maximo de 100 caracteres, si se supera el limite, esos caracteres no se contaran |
| MVP-5-9-3 | Buscar sin restricciones | El buscador de citas, realizara la busqueda teniendo en cuenta que todos los caracteres seran si o si en minuscula |
| MVP-5-9-4 | Busqueda dinamica | El buscador de citas, debera de actualizar dinamicamente los resultados segun los caracteres ingresado por la veterinaria, si son alfanumericas comparara con el nombre de la mascota y el del tutor, si son numericas, comparara con el rut del tutor y el de la mascota, para este caso, los valores se compararan sin "." ni "-" |
| MVP-5-9-5 | restauracion de las citas | El buscador debera de mostrar todas las citas cuando la veterinaria elimine los caracteres ingresados para la realizar la busqueda |
| MVP-5-9-6 | Comparacion entra la busqueda y la tabla | El buscador realizara comparacion con los datos del tutor (nombre del tutor y/o rut del tutor) y con los datos de la mascota (nombre de la mascota y/o rut de la mascota) |
| MVP-5-9-7 | Mensaje de error | El sistema debera de mostrar un mensaje diciendo "No se encuentran tutores ni mascotas con esos datos", cuando la comparacion (MVP-5-9-5) no encuentre ninguna similitud |


## Mockaps

### Ordenar citas sin error
<!-- ![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg) -->

### Ordenar citas con marca de error
<!-- ![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->