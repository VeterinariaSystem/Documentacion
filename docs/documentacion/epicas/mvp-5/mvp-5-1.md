---
sidebar_position: 2
---

# Agregar Cita

Como veterinaria necesito agregar citas para poder visualizarlas en mi sistema.

En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg)

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para agregar citas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-5-1-1 | La cita debe tener el nombre del tutor | El nombre del tutor (El campo se debe llamar "Nombre del tutor") debe tener como maximo 200 caracteres ("El nombre del tutor no puede tener más de 200 caracteres.") y como minimo 1 ("El nombre del tutor es obligatorio."), este campo se autocompleta ingresando el rut solo si el tutor se encuentra registrado (Ej: rut = "12.345.678.9" - nombre = "Juan Santana", pero rut = "98.765.432-1" - nombre = ""). |
| MVP-5-1-2 | La cita puede tener el nombre del suplente | El nombre del suplente debe tener como maximo 200 caracteres y como minimo 0 caracter (NO IMPLEMENTAR). |
| MVP-5-1-3 | La cita debe incluir el rut del tutor | El formato del rut (El campo se debe llamar "Rut del tutor") debe ser "12.345.678-9", o identificador del pais de recidencia. (El nombre del atributo rut, puede cambiar (rut/dni)). Este campo es obligatorio y no se deben aceptar cadenas vacias. En caso de que el rut no sea válido, aparecerá el siguiente mensaje “El rut no es válido.” (Ej: rut no válido = "41242671-4", rut válido = "35263123-K"), en caso de que este vacío aparecerá el siguiente mensaje “Este capo es obligatorio.” |
| MVP-5-1-4 | La cita debe tener el motivo de la consulta | El motivo (el campo debe llamarse "Motivo de consulta") debe tener como maximo 500 caracteres en caso de que este no cumpla aparecerá el siguiente mensaje "El motivo de la consulta no puede tener más de 500 caracteres.". Este campo es obligatorio y no se deben aceptar cadenas vacias, en caso de que este vacío aparecerá el siguiente mensaje “Este capo es obligatorio.”|
| MVP-5-1-5 | La cita debe tener un estado | Cuando se crea la cita (el nombre del boton para crear la cita debe ser "Crear Cita"), debe tener como estado "Aceptado" (el texto debe ser "La cita se ha creado con éxito."). En caso de que no se cumpla algun requisito no se debera poder hacer click|
| MVP-5-1-6 | La cita debe tener una fecha y hora | Se deben mostrar todos los horarios disponibles (Explicado en gestion de horarios) que tiene la veterinaria. El formato de la fecha sera la siguiente "12/01/2025" -> Y de la hora sera "20:30 hrs.". Este campo es obligatorio y no acepta informacion vacia, |
| MVP-5-1-7 | La cita debe tener un precio | la cita debe permitir agregar el precio. El cual sera un numero donde las "," seran la representacion del decimal. El formato es "$20.000 CLP", se debe representar que tipo de moneda que se cancelo. Este campo es obligatorio y no acepta informacion vacia. |
| MVP-5-1-8 | La cita debe tener el nombre de la mascota | El nombre de la mascota debe tener como maximo 200 caracteres y como minimo 1 caracter, se mostrara una lista desplegable con las mascotas ingresadas en el sistema, las cuales tengan relacion con el rut del tutor ingresado, ademas debera permitir escribir el nombre para poder econtrarla mas rapido (Autocompletar) |
| MVP-5-1-9 | La cita debe tener el numero ficha de la mascota | El numero de ficha de la mascota debe ser de tipo alfanumerico donde tendra 7 caracteres. El formato es el siguiente "#1F5P6AK". Este campo se mostrara dependiendo de la mascota que se seleccione |
| MVP-5-1-10 | La cita debe tener un ID | El id de la cita se crea de forma automatica y sera un numero | 
| MVP-5-1-11 | En caso de que se ingrese un rut que no exista | Cuando un rut no existe, debera permitirse agregar un tutor ( MVP-6 ) y luego volver a la pantalla para agregar cita pero con los datos del tutor agregado |
| MVP-5-1-12 | En caso de que no se encuentre una mascota | Cuando se requiera escoger una mascota diferente a las ingresadas al sistema, se permitira agregar una mascota ( MVP-7 ) y luego  volver a la pantalla para agregar cita pero con los datos del tutor de la mascota, y ademas los datos de la mascota agregada al sistema |
| MVP-5-1-13 | La cita debe tener un tipo de urgencia | La cita debe permitir agregar el tipo de urgencia, las cuales pueden ser "Alta", "Media" y "Baja", este campo es obligatorio. |



## Mockaps

### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg)