Tipos de Pruebas
_____________________________________________________________________________

Pruebas Funcionales
Objetivo: Verificar que las funcionalidades cumplen con los requerimientos.

Registro de usuario:	Verificar que un nuevo usuario puede registrarse correctamente.	Nombre, correo electrónico, contraseña
El usuario recibe una confirmación y se le redirige a la página principal.

Inicio de sesión:	Probar que los usuarios pueden iniciar sesión con sus credenciales.	Correo electrónico, contraseña	Acceso a la cuenta del usuario con su perfil.

Registro de lanzamiento:	Validar que los tiros se registran con precisión (acierto/fallo).	Número de aciertos y fallos	Los datos de lanzamiento se actualizan en el perfil del usuario.

Cálculo de porcentaje de tiro:	Probar que el cálculo de aciertos/fallos es preciso y se refleja en el perfil.	

Total de tiros y aciertos: El porcentaje de acierto se muestra correctamente en el perfil.

Ranking de jugadores:	Verificar que el sistema de ranking muestra correctamente la posición del usuario.	

Puntuación total de usuarios:	El ranking ordena a los jugadores de mayor a menor porcentaje de acierto.

Compartir estadísticas:	Comprobar que el usuario puede compartir su rendimiento con otros jugadores.	

Datos del perfil del usuario:	El perfil del usuario se puede compartir con otros jugadores de la app.

Acceso a videos instructivos:	Validar que los videos de entrenamiento se cargan y reproducen sin problemas.

Contenido de video:	El video se carga y se reproduce correctamente.

_____________________________________________________________________________

Pruebas de Interfaz de Usuario (UI)
Objetivo: Evaluar la usabilidad, accesibilidad y navegación de la interfaz.

Pantalla de inicio:	Verificar que todos los elementos de la pantalla se muestran correctamente.	Los botones y campos son visibles y responden al toque.

Navegación:	Probar la navegación entre pantallas (perfil, ranking, videos).	La navegación es fluida y sin errores.

Responsividad:	Validar que la aplicación se ajusta bien a diferentes tamaños de pantalla.	La interfaz se adapta sin distorsión en dispositivos de distintos tamaños.

Accesibilidad:	Asegurarse de que los elementos interactivos son accesibles para usuarios con discapacidad.	Todos los elementos son navegables y legibles con lectores de pantalla.

_____________________________________________________________________________

Pruebas de Rendimiento
Objetivo: Asegurar que la aplicación responde bien bajo distintas condiciones de uso.

Carga: Verificar el tiempo de carga de la aplicación al inicio.	La app inicia en menos de 3 segundos.

Respuesta en el registro de tiros:	Medir el tiempo de respuesta al registrar tiros.	El tiempo de respuesta es inferior a 1 segundo.

Rendimiento con múltiples usuarios:	Probar el rendimiento en condiciones de carga alta (múltiples usuarios activos).	La aplicación mantiene un rendimiento aceptable sin ralentizarse.

_____________________________________________________________________________

Pruebas de Seguridad
Objetivo: Garantizar que la aplicación protege los datos de los usuarios y se mantiene segura.

Autenticación:	Probar la seguridad del inicio de sesión.	Solo los usuarios registrados pueden acceder.

Protección de datos:	Verificar que los datos de usuario están encriptados y protegidos.	Los datos de usuario están encriptados y no se exponen.

Prevención de ataques:	Probar la resistencia a intentos de acceso no autorizados.	La aplicación detecta y bloquea intentos de acceso ilegales.
