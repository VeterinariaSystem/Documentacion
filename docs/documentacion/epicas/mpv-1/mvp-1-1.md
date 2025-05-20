---
sidebar_position: 20
---

# Gestionar mi Perfil de Tutor

Como tutor, necesito poder actualizar mi información de contacto (número de celular y ubicación) y recibir confirmación de estos cambios, para asegurar que la comunicación con las veterinarias sea efectiva y mi información de localización para servicios esté al día.

## Criterios de Aceptación (C.A.)
Son los criterios de aceptación para la gestión del perfil del tutor:

| Id        | C.A.                                      | Descripción                                                                                                                               |
|-----------|-------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| MVP-1-1-1 | Acceso a la sección de perfil             | El sistema debe permitir al tutor acceder a una sección donde pueda ver y modificar su información de perfil.                               |
| MVP-1-1-2 | Modificar número de celular               | El sistema debe permitir al tutor editar y guardar un nuevo número de celular.                                                              |
| MVP-1-1-3 | Formato de número de celular              | El sistema debe validar el formato del número de celular según el país de residencia (ej. +569XXXXXXXX para Chile).                       |
| MVP-1-1-4 | Modificar ubicación (comuna/región)       | El sistema debe permitir al tutor editar y guardar su ubicación, seleccionando comuna y/o región de una lista predefinida o mediante geolocalización. |
| MVP-1-1-5 | Campos no modificables por el tutor     | El sistema debe mostrar, pero no permitir la modificación por parte del tutor, de datos como RUT, nombre completo, correo electrónico (establecidos durante el registro). |
| MVP-1-1-6 | Confirmación de guardado                  | Al guardar los cambios, el sistema debe mostrar un mensaje de confirmación de que la información ha sido actualizada exitosamente.             |
| MVP-1-1-7 | Notificación por correo de actualización  | Tras una actualización exitosa del perfil (teléfono o ubicación), el sistema debe enviar un correo electrónico de confirmación al tutor  |