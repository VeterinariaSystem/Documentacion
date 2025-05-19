---
sidebar_position: 20
---

# Eliminar Ficha

Como veterinaria necesito eliminar fichas para poder liberar espacio en mi sistema.

<!-- En la siguiente imagen reprecenta el flujo general de la historia de usuario:
![Task Flow de Gestionar citas](/img/gestionar_citas/agregar_cita/agregar_cita_diagrama.svg) -->

## Criterios de Aceptacion
Son los criterios de aceptacion (C.A.) para eliminar fichas:

| Id | C.A. | Descripcion | 
|-------------------- | -------- | -------- | 
| MVP-7-3-1 | Ficha en sistema| La ficha debe estar ingresado en el sistema para poder eliminar los datos. |
| MVP-7-3-2 | Mostrar confirmacion de eliminacion de ficha | Al presionar la opcion para eliminar, se abrira un modal diciendo: "La ficha se eliminara definitivamente" mas la opcion de confirmar y cancelar |
| MVP-7-3-3 | Confirmacion de eliminar ficha de mascota | Al confirmar la eliminacion de la ficha, el sistema eliminara los datos de la ficha(visualmente) y mostrara el mensaje "La ficha ha sido eliminada exitosamente", en caso de que no se haya podido eliminar, se mostrara el mensaje "Hubo un error al eliminar la ficcha". |
| MVP-7-3-4 | Actualizacion del sistema luego de eliminar la ficha | Una vez eliminada la ficha, el sistema se actualizara sin los datos de este. |

## Mockaps

<!-- ### Agregar sin error
![Mockap de Gestionar citas general](/img/gestionar_citas/agregar_cita/agregar_cita_mockap.svg)

### Agregar con marca de error
![Mockap de Gestionar citas tabla](/img/gestionar_citas/agregar_cita/agregar_cita_error_mockap.svg) -->