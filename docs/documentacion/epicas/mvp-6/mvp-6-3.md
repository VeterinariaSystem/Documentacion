---
sidebar_position: 13
---

# Eliminar Tutor

Como veterinaria necesito eliminar tutores para poder tener limpio mi sistema.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para eliminar tutores:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-6-3-1 | Tutor en sistema| El tutor debe estar ingresado en el sistema para poder eliminar sus datos |
| MVP-6-3-2 | Mostrar confirmacion de eliminacion del tutor | Al presionar la opcion para eliminar, se abrira un modal diciendo: "El perfil se eliminara definitivamente" mas la opcion de confirmar y cancelar |
| MVP-6-3-3 | Confirmacion de eliminar tutor | Al confirmar la eliminacion del perfil del tutor, el sistema eliminara los datos de solo el tutor y mostrara el mensaje "La cuenta ha sido eliminada exitosamente", a su vez, generara un correo notificando la accion al tutor, en caso de que no se haya podido eliminar, se mostrara el mensaje "Hubo un error al eliminar la cuenta". |
| MVP-6-3-4 | Actualizacion del sistema luego de eliminar al tutor | Una vez eliminado el tutor, el sistema se actualizara sin los datos de este. |


## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->