---
sidebar_position: 8
---

# Filtrar Citas
Como veterinaria necesito filtrar las citas en mi sistema tener una mejor visualizacion de estas.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario: -->
<!-- ![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para filtrar citas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-5-7-1 | Mostrar filtro por estado | El sistema debera de mostrar las opciones "Aceptado", "Cancelado", "Pendiente" y "ninguno" para poder filtrar por el estado de la cita. |
| MVP-5-7-2 | Filtrar por estado | EL sistema debera de mostrar los datos de la citas que su estado sea el mismo que el seleccionado por el usuario, en caso de ser "Ninguno", no se aplicara restricciones a los datos. |
| MVP-5-7-3 | Mostrar filtro por fecha | El sistema debera de mostrar la opcion de ingresar dos fechas tentativas en formato "DD-MM-YYYY". |
| MVP-5-7-4 | Filtrar por fecha | El sistema solo se mostrara los datos que se encuentren entre las fechas tentativas ingresadas. |
| MVP-5-7-5 | Mostrar filtro por tipo de urgencia | El sistema debera de mostrar las opciones "Alta", "Media", "Baja" y "ninguno" para poder filtrar por el tipo de urgencia de la cita.  |
| MVP-5-7-6 | Filtrar por tipo de urgencia | EL sistema debera de mostrar los datos de la citas que su tipo de urgencia sea el mismo que el seleccionado por el usuario, en caso de ser "Ninguno", no se aplicara restricciones a los datos. |



## Mockaps

### Filtrar citas sin error
<!-- ![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg) -->

### Filtrar citas con marca de error
<!-- ![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->