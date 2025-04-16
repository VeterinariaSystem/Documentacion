---
sidebar_position: 3
---

# Cancelar Cita
Como veterinaria necesito cancelar las citas para tener disponibilidad en mi sistema.

En la siguiente imagen reprecenta el flujo general de la historia de usuario:
<!-- ![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para cancelar citas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-5-2-1 | La cita debe tener estado "Aceptado" | La opcion de cancelar solo sera visible si la cita se encuentra en el estado "Aceptado" |
| MVP-5-2-2 | Mostrar confirmacion para cancelar la cita | Al presionar la opcion para cancelar, se desplegara un dialogo para confirmar la cancelacion de la cita |
| MVP-5-2-3 | Notificar la cancelacion de la cita al tutor | Cuando la veterinaria cancela la cita, se notificara al tutor mediante un correo con los datos de la cita permitiendo reagendarla |
| MVP-5-2-4 | Notificar la cancelacion de la cita a la veterinaria | Cuado el tutor cancela la cita, se notificara a la veterinaria mediante un correo con los datos de a cita |
| MVP-5-2-5 | La cita cambiara de estado a "Cancelada" | Al terminar el proceso, el estado de la cita se debera de mostrar como "Cancelada" dentro del sistema |
| MVP-5-2-6 | Actualizar la disponibilidad de la veterinaria | El sistema debera de desocupar la hora tomada y actualizarlo en el sistema |


## Mockaps

### Cancelar sin error
<!-- ![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg) -->

### Cancelar con marca de error
<!-- ![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->