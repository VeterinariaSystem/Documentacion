---
sidebar_position: 4
---

# Modificar Cita
Como veterinaria necesito modificar los datos de las citas para tener la informacion correcta y/o actualizada en mi sistema.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario: -->
<!-- ![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para modificar citas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-5-3-1 | La cita debe tener estado "Aceptado" | La opcion de modificar solo sera visible si la cita se encuentra en el estado "Aceptado" |
| MVP-5-3-2 | Mostrar datos de la cita | Al presionar la opcion para modificar, se abrira el formulario de la cita con los datos llenos |
| MVP-5-3-3 | La cita puede tener el nombre del suplente (NO APLICA) | El nombre del suplente debe tener como maximo 200 caracteres y como minimo 0 caracter. El nombre podra ser modificado por el tutor y la veterinaria |
| MVP-5-3-4 | La cita debe tener el motivo de la consulta | El motivo debe tener como maximo 500 caracteres. Este campo es obligatorio y no se deben aceptar cadenas vacias. campo no modificable |
| MVP-5-3-5 | La cita debe tener una fecha y hora | Se deben mostrar todos los horarios disponibles (Explicado en gestion de horarios) que tiene la veterinaria. El formato de la fecha sera la siguiente "12/01/2025" -> Y de la hora sera "20:30 hrs.". Este campo es obligatorio y no acepta informacion vacia. Este valor es modificable  |
| MVP-5-3-6 | La cita debe tener un precio | la cita debe permitir agregar el precio. El cual sera un numero donde las "," seran la representacion del decimal. El formato es "$20.000 CLP", se debe representar que tipo de moneda se cancelo. Este campo es obligatorio y no acepta informacion vacia. El precio solo podra ser modificado por la veterinaria |
| MVP-5-3-7 | La cita debe tener el nombre de la mascota | El nombre de la mascota debe tener como maximo 200 caracteres y como minimo 1 caracter. Se mostrara una lista desplegable con las mascotas ingresadas al sistema, ademas de permitir escribir el nombre para poder econtrarla mas rapido (Autocomple). Nombre no modificable |
| MVP-5-3-8 | La cita debe tener el numero ficha de la mascota | El numero de ficha de la mascota debe ser de tipo alfanumerico donde tendra 7 caracteres. El formato es el siguiente "#1F5P6AK". Este campo se mostrara dependiendo de la mascota que se seleccione. Campo no modificable |
| MVP-5-3-9 | La cita debe tener un ID | El id de la cita se crea de forma automatica y sera un numero. Campo no modificable | 
| MVP-5-3-10 | Modificar los datos de la cita | Al presionar "Modificar", si todos los datos son validos, el sistema actualizara la cita con los datos nuevos |
| MVP-5-3-11 | Notificar la modificacion de la cita al tutor | Cuando la veterinaria modifique la cita, se notificara al tutor mediante un correo con los nuevos datos modificados |
| MVP-5-3-12 | Notificar la modificacion de la cita a la veterinaria | Cuado el tutor modifique la cita, se notificara a la veterinaria mediante un correo con los nuevos datos de a cita |
| MVP-5-3-13 | Modificar tipo de urgencia de la cita | La cita debe permitir modificar el tipo de urgencia, las cuales pueden ser "Alta", "Media" y "Baja", este campo es modificable. |


## Mockaps

### Modificar sin error
<!-- ![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg) -->

### Modificar con marca de error
<!-- ![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->