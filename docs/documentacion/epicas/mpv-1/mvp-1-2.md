---
sidebar_position: 21
---

# Gestionar mis Mascotas

Como tutor, necesito poder agregar nuevas mascotas a mi perfil, ver la lista de mis mascotas registradas, modificar su información y archivar mascotas que ya no están bajo mi cuidado, para mantener un registro actualizado y preciso de ellas.

## Criterios de Aceptación (C.A.)
Son los criterios de aceptación para la gestión de mascotas por el tutor:

| Id        | C.A.                                      | Descripción                                                                                                                                |
|-----------|-------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| MVP-1-2-1 | Acceso a la sección de mascotas           | El sistema debe permitir al tutor acceder a una sección donde pueda gestionar sus mascotas.                                                 |
| MVP-1-2-2 | Límite de mascotas                        | El sistema debe permitir al tutor registrar un máximo de 10 mascotas.                                                                      |
| MVP-1-2-3 | Agregar nueva mascota                     | El sistema debe proveer un formulario para que el tutor ingrese los datos de una nueva mascota.                                              |
| MVP-1-2-4 | Campos para agregar mascota               | Los campos para agregar una mascota deben ser: Nombre (obligatorio, máx. 200 char), Apellido (opcional, máx. 200 char), Especie (obligatorio, lista), Fecha de Nacimiento (obligatorio, DD-MM-YYYY), Raza (obligatorio, máx. 200 char), Sexo (Macho/Hembra), Enfermedades preexistentes (opcional, máx. 500 char). |
| MVP-1-2-5 | Generación ID de mascota                  | El sistema generará un identificador único para la mascota de forma automática al ser agregada (no visible/editable por el tutor como campo de ingreso). |
| MVP-1-2-6 | Ver lista de mascotas                     | El sistema debe mostrar al tutor una lista de sus mascotas registradas (no archivadas), con información resumida (ej. nombre, especie, raza). |
| MVP-1-2-7 | Ver detalle de mascota                    | Al seleccionar una mascota de la lista, el sistema debe mostrar todos sus detalles.                                                        |
| MVP-1-2-8 | Modificar mascota                         | El sistema debe permitir al tutor modificar la información previamente registrada de cualquiera de sus mascotas (los mismos campos de agregar). |
| MVP-1-2-9 | Archivar mascota (Quitar)                 | El sistema debe permitir al tutor "quitar" (archivar) una mascota. La mascota archivada no aparecerá en la lista activa pero su historial se conservará. |
| MVP-1-2-10| Confirmación de acciones                  | El sistema debe mostrar mensajes de confirmación para acciones como agregar, modificar o archivar una mascota.                               |