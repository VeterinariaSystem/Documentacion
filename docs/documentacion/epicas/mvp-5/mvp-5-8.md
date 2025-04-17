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
| MVP-5-9-1 | Limitar caracteres en el buscador | El buscador de citas, tendra un maximo de 100 caracteres, si se supera el limite, no se podra seguir escribiendo. |
| MVP-5-9-2 | Busqueda con caracteres en minuscula | El buscador de citas, realizara la busqueda teniendo en cuenta que todos los caracteres seran si o si en minuscula. |
| MVP-5-9-3 | Busqueda sin caracteres especiales | El buscador de citas, realizara la busqueda teniendo en cuenta que todos los caracteres no seran especiales. |
| MVP-5-9-4 | Busqueda dinamica | El buscador de citas, debera de actualizar dinamicamente los resultados segun los caracteres ingresado el usuario, haciendo comparacion con todos los datos de la tabla (id, tutor, motivo, estado, tipo de urgencia, precio y mascota). |
| MVP-5-9-5 | Restauracion de las citas | El buscador debera de mostrar todas las citas cuando el usuario elimine los caracteres ingresados para la realizar la busqueda. |
| MVP-5-9-6 | Restauracion de los caracteres de la busqueda cuando se cambia de pagina | Cuando se recarga la pagina los caracteres escritos en el buscador, deberan de ser eliminados. |
| MVP-5-9-7 | Mantener datos de busqueda al abrir ventanas emergentes | los datos de busqueda no se deberan de actualizar al abrir/cerrar una ventana emergente. |
| MVP-5-9-8 | Mensaje de error de busqueda | El sistema debera de mostrar un mensaje diciendo "No se encuentran citas relacionadas", cuando la comparacion no encuentre ninguna similitud. |


## Mockaps

### Buscar citas sin error
<!-- ![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg) -->

### Buscar citas con marca de error
<!-- ![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->