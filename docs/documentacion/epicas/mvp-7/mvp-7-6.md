---
sidebar_position: 23
---

# Buscar Fichas

Como veterinaria necesito buscar las fichas que se encuentran en mi sistema para tener acceso a su informacion mas rapido.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para buscar fichas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-7-6-1 | Limitar caracteres en el buscador | El buscador de fichas, tendra un maximo de 100 caracteres, si se supera el limite, no se podra seguir escribiendo. |
| MVP-7-6-2 | Busqueda con caracteres en minuscula | El buscador de fichas, realizara la busqueda teniendo en cuenta que todos los caracteres seran si o si en minuscula. |
| MVP-7-6-3 | Busqueda sin caracteres especiales | El buscador de fichas, realizara la busqueda teniendo en cuenta que todos los caracteres no seran especiales. |
| MVP-7-6-4 | Busqueda dinamica | El buscador de fichas, debera de actualizar dinamicamente los resultados segun los caracteres ingresado por el usuario, haciendo comparacion con todos los datos de la tabla de fichas (Nombre de la mascota, apellido de la mascota, identificador de la ficha, tipo de especie, fecha de nacimiento de mascota, años de la mascota, raza de la mascota, sexo de la mascota, enfermedades de la mascota). |
| MVP-7-6-5 | Restauracion de la busqueda de fichas | El buscador debera de mostrar todoas las fichas cuando el usuario elimine los caracteres ingresados para la realizar la busqueda. |
| MVP-7-6-6 | Restauracion de los caracteres de la busqueda cuando se cambia de pagina | Cuando se recarga la pagina los caracteres escritos en el buscador, deberan de ser eliminados. |
| MVP-7-6-7 | Mantener datos de busqueda al abrir ventanas emergentes | los datos de busqueda no se deberan de actualizar al abrir/cerrar una ventana emergente. |
| MVP-7-6-8 | Mensaje de error de busqueda | El sistema debera de mostrar un mensaje diciendo "No se encuentran fichas relacionadas", cuando la comparacion no encuentre ninguna similitud. |

## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->