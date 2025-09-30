# ProyectoD

planificacion del sprint 1 de Bon apettit
1- planificar el objetivo
2- asignacion de roles
3- Se definen los sprint
4- subdividir las tareas del sprint
5- hacer reuniones
6 -Revisión de subtareas

Planificación Diaria (Lunes a Viernes)
Lunes: Registro de Usuarios (Diseño y Componente)
Comenzamos el sprint enfocándonos en la Página de Registro. La tarea principal es el diseño de la interfaz y la creación del Componente Registro en el frontend. Usaremos useState para manejar el estado de todos los campos de entrada y la lógica de la vista. Cerramos el día asegurando que la Validación de datos de entrada básica (como el formato del correo y la longitud de la contraseña) esté implementada en el lado del cliente.

Martes: Registro (Integración con el Backend)
Este día se centra en la conexión con la API para el registro. Tomamos los datos validados del componente de registro para enviarlos al backend. Nuestro enfoque estará en establecer la comunicación de la API y el manejo robusto de la respuesta de la API, ya sea para confirmar la creación exitosa del usuario o para mostrar mensajes de error específicos.

Miércoles: Login y Autenticación (Diseño)
Pasamos a la funcionalidad de Inicio de Sesión. Crearemos el Componente Login y, al igual que el registro, utilizaremos useState para los campos de email y contraseña. La tarea clave es llamar a la API de login al enviar el formulario. El día incluye la configuración para manejar la respuesta de la API, que debe contener el token de autenticación.

Jueves: Login y Autenticación (Gestión de Sesión)
El jueves es crucial para la experiencia del usuario, pues implementamos la persistencia de la sesión. Los pasos incluyen guardar el token en el almacenamiento local (localStorage o AsyncStorage), configurar la Context API para que la información del usuario (su estado de sesión) esté disponible en toda la aplicación, y implementar la navegación con react-router-dom para redirigir al usuario inmediatamente después de iniciar sesión.

Viernes: Listado de Pastelerías (Diseño y Datos)
Iniciamos la sección de catálogo con el diseño de la Página de Listado. Crearemos el Componente Listado y estableceremos la lógica para llamar a la API que nos devolverá el listado de pastelerías. Nos enfocaremos en la experiencia del usuario al manejar los estados de carga y error visibles en la interfaz y en la renderización de las pastelerías en una grilla o flexbox.

