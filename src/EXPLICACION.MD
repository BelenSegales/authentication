Instalaciones realizadas!

npm install axios react-router-dom zustand react-hook-form zod @hookform/resolvers

// AXIOs una librería cliente HTTP basada en promesas para realizar peticiones al servidor.  
Para qué nos sirve? Permite conectar tu frontend con la API, configurar una URL base, usar interceptores automáticos para inyectar el token Bearer en cada request y manejar errores de forma centralizada.

// react-router-dom La librería oficial para manejar el enrutamiento en aplicaciones React de tipo SPA (Single Page Application).  
Para qué nos sirve? Gestiona la navegación por URL sin recargar la página completa, permitiendo renderizar diferentes vistas (Routes, Route), usar enlaces dinámicos (NavLink, Link), capturar parámetros (useParams) y navegar por código (useNavigate).

// zustand es una librería ligera de gestión de estado global.  
Para qué nos sirve? Resuelve el problema del prop drilling guardando datos compartidos (como la sesión del usuario o el token) accesibles desde cualquier componente, y permite usar el middleware persist para mantener la sesión activa aunque el usuario recargue con F5.

// react-hook-form una librería para optimizar y controlar formularios en React.  
Para qué nos sirve? Gestiona los campos de manera eficiente mediante componentes no controlados, evitando que toda la pantalla se re-renderice en cada tecla que escribe el usuario.

// zod una librería para la declaración y validación de esquemas orientada a TypeScript.  
Para qué nos sirve? Permite definir reglas estrictas para los datos (como validar formatos de correo electrónico o mínimos de caracteres en contraseñas) antes de enviarlos a la API, generando automáticamente los tipos estáticos.

// @hookform/resolvers un paquete integrador de validaciones para formularios.  
Para qué nos sirve? Actúa como un puente (zodResolver) que conecta los esquemas de validación de Zod directamente con React Hook Form para mostrar los errores por campo en la interfaz.
