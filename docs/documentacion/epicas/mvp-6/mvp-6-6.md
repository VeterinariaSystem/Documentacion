---
sidebar_position: 16
---

# Buscar Tutores

Como veterinaria necesito buscar los tutores que se encuentran en mi sistema para tener acceso a su informacion mas rapido.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para buscar tutores:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-6-6-1 | Limitar caracteres en el buscador | El buscador de tutores, tendra un maximo de 100 caracteres, si se supera el limite, no se podra seguir escribiendo. |
| MVP-6-6-2 | Busqueda con caracteres en minuscula | El buscador de tutores, realizara la busqueda teniendo en cuenta que todos los caracteres seran si o si en minuscula. |
| MVP-6-6-3 | Busqueda sin caracteres especiales | El buscador de tutores, realizara la busqueda teniendo en cuenta que todos los caracteres no seran especiales. |
| MVP-6-6-4 | Busqueda dinamica | El buscador de tutores, debera de actualizar dinamicamente los resultados segun los caracteres ingresado por el usuario, haciendo comparacion con todos los datos de la tabla de tutores (nombre, apellidos, rut/dni, correo, numero telefonico, direccion y el pais de residencia). |
| MVP-6-6-5 | Restauracion de la busqueda de tutores | El buscador debera de mostrar todos los tutores cuando el usuario elimine los caracteres ingresados para la realizar la busqueda. |
| MVP-6-6-6 | Restauracion de los caracteres de la busqueda cuando se cambia de pagina | Cuando se recarga la pagina los caracteres escritos en el buscador, deberan de ser eliminados. |
| MVP-6-6-7 | Mantener datos de busqueda al abrir ventanas emergentes | los datos de busqueda no se deberan de actualizar al abrir/cerrar una ventana emergente. |
| MVP-6-6-8 | Mensaje de error de busqueda | El sistema debera de mostrar un mensaje diciendo "No se encuentran tutores relacionadas", cuando la comparacion no encuentre ninguna similitud. |

## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->