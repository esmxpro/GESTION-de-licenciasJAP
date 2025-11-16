📌Sistema de Pedido de Licencias Docentes
🎯 Objetivo del Software

Este sistema tiene como finalidad gestionar las solicitudes de licencias de los profesores de forma digital y organizada.
Permite registrar a los docentes, guardar sus datos personales y facilitar el proceso de solicitud, aprobación y control de licencias laborales, reemplazando procesos manuales o en papel.
🧠 Tecnologías Utilizadas

🐍 Python — Lenguaje principal del backend

🌐 Flask — Framework web para manejar rutas y lógica del servidor

💾 SQLite — Base de datos ligera para almacenar información de profesores y licencias

🎨 HTML, CSS y JavaScript — Interfaz visual del sistema

🧱 Bootstrap / Tailwind (opcional) — Para el diseño adaptable y moderno

⚙️ Git & GitHub — Control de versiones y colaboración en equipo
👥 Autores e Integrantes del Equipo
Nombre:

💻 Desarrolladores:
- Esmeralda Gutiérrez
- Yerani Lizarraga

🧩 Estructura de la Base de Datos

El sistema cuenta con dos tablas principales:

🧑‍🏫 profesores
Campo Tipo Descripción
id INTEGER (PK) Identificador único del profesor
nombre TEXTO Nombre completo
carnet TEXTO (ÚNICO) Identificador único de docente
contrasena TEXTO Contraseña de acceso
turno TEXTO Turno laboral (mañana, tarde, noche)
especialidad TEXTO Área o materia de especialización
📝 licencias
Campo Tipo Descripción
id INTEGER (PK) Identificador de la solicitud
profesor_id INTEGER (FK) Relación con el profesor
fecha TEXT Fecha de solicitud
motivo TEXTO Motivo de la licencia
estado TEXTO (DEFAULT 'En espera') Estado de aprobación
fecha_inicio TEXTO Inicio de la licencia
fecha_fin TEXTO Fin de la licencia

🌐 Enlace del Despliegue
Descarga o clona el proyecto desde GitHub
Abra la carpeta del proyecto en su editor de preferencia (como VS Code).

Crea y activa un entorno virtual para mantener las dependencias organizadas.
Crea y activa un entorno virtual para mantener las dependencias organizadas.
Instale las dependencias necesarias con: pip install -r requisitos.txt
Ejecuta la aplicación para iniciar el servidor local con: python app.py
Abra su navegador web y navegue a http://localhost:5000 para acceder al sistema de licencias docentes.
¡Listo! Ahora puedes registrar docentes, solicitar licencias y gestionar aprobaciones de manera digital.