## 1. Descripción del proyecto

### Nombre del sistema
Vugo

### Problema que resuelve
En este momento, muchos profesionales de la salud mental gestionan sus citas de forma manual o mediante herramientas genéricas, lo que genera errores en la disponibilidad, falta de recordatorios y una gestión ineficiente de la información de los pacientes. Este sistema centraliza el proceso de agendamiento, permitiendo una organización óptima del tiempo del profesional y facilidad de acceso para el usuario.

### Usuarios del sistema
* **Administradores:** Tienen el control absoluto del sistema tanto de acciones dentro de los módulos como del resto de usuarios existentes, sin importar los permisos asignados.
* **Recepcionistas:** Tienen la capacidad de hacer un uso más general del sistema como la creación de citas, edición de usuarios, etc. Siempre y cuando cuenten con los respectivos permisos.
* **Psicólogos:** Gestionan su disponibilidad, revisan sus citas programadas y administran el perfil de sus pacientes.
* **Pacientes (Usuarios finales):** Pueden registrarse, visualizar horarios disponibles y agendar o cancelar citas de manera autónoma.

### Funcionalidades principales
* **Gestión de Autenticación:** Registro e inicio de sesión seguro para pacientes, psicólogos, recepcionistas y administradores (Django Auth).
* **Agendamiento en Tiempo Real:** Interfaz dinámica para seleccionar fechas y horas disponibles validando la existencia de los pacientes previamente creados.
* **Panel de Control (Dashboard):** Visualización de las próximas citas tanto para el psicólogo (únicamente las citas de cada uno) como para el resto de roles.
* **Interfaz Adaptable:** Diseño moderno y responsivo construido con Tailwind CSS para facilitar el uso desde móviles o computadores.