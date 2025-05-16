---
sidebar_position: 1
---

# Propuesta de solución
Nosotros trabajaremos en un sistema donde se podrá gestionar a las veterinarias.

## Objetivos
(Por definir)

## Glosario general
En la siguiente tabla muestra la definición de cada palabra a utilizar:

| Nombre      | Descripción                                 |
|-------------|---------------------------------------------|
| Tutor       | Dueño de una mascota                       |
| Veterinaria | Usuarios que trabajan en la veterinaria     |
| Mascota     | Mascota la cual está asociada a un tutor    |
| Citas       | Cuando los tutores van a la veterinaria para que atiendan a sus mascotas |

## Épicas
Son las funcionalidades del sistema.

### Épicas generales
- Módulo para el tutor
- Envíos de correos personalizados
- Módulos de pago
- Sistema de autenticación
- Gestión de usuarios y roles
- Gestión de citas
- Gestión de inventarios
- Creación de informes
- Gestión de tutores y fichas
- Gestión de laboratorio
- Gestión de hospitalización
- Panel de administrador
- Buscador de datos

### Épicas para el MVC

| Id     | Épicas                       | Descripción                                                                                   | Prioridad                                                                                              |
|--------|------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| MVP-1  | Módulo para el tutor         | Sistema que permite al tutor gestionar a sus mascotas.                                               | <div style={{backgroundColor: "#f2a93b", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Mediana</div>  |
| MVP-2  | Envíos de correos personalizados | Sistema que permite enviar correos automáticos con personalización según los datos del usuario. | <div style={{backgroundColor: "#25c2a0", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Baja</div> |
| MVP-3  | Sistema de autenticación     | Autenticación segura con roles de usuario.                                                   | <div style={{backgroundColor: "#f2a93b", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Mediana</div>  |
| MVP-4  | Gestión de usuarios y roles  | Módulo para administrar usuarios y sus roles.                                                | <div style={{backgroundColor: "#f2a93b", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Mediana</div>    |
| [MVP-5](./epicas/mvp-5#historias-usuario)  | Gestión de citas             | Agenda integrada para organizar citas entre profecionales y tutores de las mascotas.                               | <div style={{backgroundColor: "#f25c5c", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Alta</div>  |
| MVP-6 | Gestión de tutores  | Sistema que gestiona a los tutores | <div style={{backgroundColor: "#f25c5c", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Alta</div>  |
| MVP-7 | Gestión de fichas | Sistema que gestiona las fichas de las mascotas | <div style={{backgroundColor: "#f25c5c", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Alta</div>  |
| MVP-8 | Buscador de datos | Permite buscar cualquier dato mediante un texto ingresado | <div style={{backgroundColor: "#25c2a0", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Baja</div>  |
| MVP-9 | Gestor de horario disponible | Sistema permite gestionar el horario disponible de la veterinaria | <div style={{backgroundColor: "#f2a93b", color: "white", display: "inline-block", padding: "5px 10px", borderRadius: "20px"}}>Mediana</div>    |
