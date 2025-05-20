---
sidebar_position: 23
---

# Gestionar Citas para mis Mascotas

Como tutor, necesito poder agendar nuevas citas para mis mascotas seleccionando una veterinaria y horario disponible, ver mis citas programadas, modificar (reagendar, cambiar motivo/mascota) y cancelar citas existentes, además de recibir notificaciones por correo sobre estas acciones, para administrar eficientemente la atención veterinaria de mis mascotas.

## Criterios de Aceptación (C.A.)
Son los criterios de aceptación para la gestión de citas por el tutor:

| Id        | C.A.                                      | Descripción                                                                                                                                  |
|-----------|-------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| MVP-1-4-1 | Acceso a gestión de citas                 | El sistema debe permitir al tutor acceder a una sección para gestionar sus citas.                                                           |
| MVP-1-4-2 | Agendar nueva cita: Selección de mascota  | Al agendar, el tutor debe poder seleccionar para cuál de sus mascotas registradas es la cita.                                                 |
| MVP-1-4-3 | Agendar nueva cita: Motivo                | El tutor debe poder ingresar el motivo de la consulta para la nueva cita.                                                                    |
| MVP-1-4-4 | Agendar nueva cita: Selección veterinaria/horario | El tutor debe poder seleccionar una veterinaria (de la lista de búsqueda/cercanas) y ver sus horarios disponibles (bloques definidos por MVP-9) para elegir uno. |
| MVP-1-4-5 | Confirmación de cita agendada             | Al finalizar el agendamiento, el sistema debe mostrar una confirmación de la cita con todos los detalles.                                    |
| MVP-1-4-6 | Ver listado de citas                      | El sistema debe mostrar al tutor un listado de sus citas futuras y pasadas, con información clave (mascota, veterinaria, fecha, hora, estado). |
| MVP-1-4-7 | Modificar cita: Reagendar                 | El tutor debe poder seleccionar una cita futura y modificar su fecha y/o hora, eligiendo un nuevo horario disponible en la misma veterinaria.  |
| MVP-1-4-8 | Modificar cita: Cambiar motivo/mascota    | El tutor debe poder modificar el motivo de la consulta o cambiar la mascota asociada a una cita futura.                                      |
| MVP-1-4-9 | Cancelar cita                             | El tutor debe poder cancelar una cita futura.                                                                                                 |
| MVP-1-4-10| Sin limitaciones estrictas (Tutor)        | Para MVP-1, no se definen limitaciones estrictas de tiempo de antelación para que el tutor modifique o cancele citas (sujeto a revisión futura). |
| MVP-1-4-11| Notificación por correo: Agendar          | Al agendar una cita, el tutor recibirá un correo de confirmación (enlace MVP-2).                                                              |
| MVP-1-4-12| Notificación por correo: Modificar        | Al modificar una cita, el tutor recibirá un correo con los detalles actualizados (enlace MVP-2).                                               |
| MVP-1-4-13| Notificación por correo: Cancelar         | Al cancelar una cita, el tutor recibirá un correo de cancelación (enlace MVP-2).                                                              |
| MVP-1-4-14| Notificación por correo: Recordatorio     | El sistema enviará correos recordatorios antes de las citas programadas (enlace MVP-2).                                                       |