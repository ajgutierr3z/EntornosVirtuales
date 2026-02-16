#Programación de Entornos Virtuales.

Este proyecto es un prototipo funcional de un entorno virtual 3D desarrollado para la materia de Programación de Entornos Virtuales.

La particularidad de este proyecto es que sustituimos los controles tradicionales (teclado/mouse) por una Interfaz de Usuario Natural (NUI) basada en Inteligencia Artificial, utilizando únicamente tecnologías web estándar.

Objetivo
Integrar la librería de visión artificial MediaPipe con el motor gráfico Three.js para crear una experiencia interactiva donde el "vibe" (gestos faciales) del usuario controle el movimiento y la estética de un vehículo en un entorno 3D.

Tecnologías Utilizadas
* HTML5 / CSS3: Estructura y diseño de la interfaz.
* JavaScript (ES6+): Lógica del juego y módulos.
* Three.js: Motor de renderizado 3D (WebGL).
* MediaPipe / TensorFlow.js: Modelos de IA para el reconocimiento de puntos faciales (Face Landmarker).

Instalación y Uso Local
Dado que el proyecto utiliza módulos de JavaScript y requiere acceso a la cámara, no se puede ejecutar abriendo el archivo directamente. Debe servirse a través de un protocolo http o https.

Opción A: Servidor Local (Apache/XAMPP)
Descarga el archivo index.html.

Colócalo en tu carpeta htdocs (XAMPP) o www (WAMP).
* Accede desde tu navegador a http://localhost/nombre-de-tu-carpeta/index.html.

Opción B: VS Code (Live Server)
* Abre la carpeta del proyecto en VS Code.
* Haz clic derecho sobre index.html y selecciona "Open with Live Server".

Controles del "Vibe"
* Dirección: Inclina o mueve tu cabeza a la izquierda o derecha para dirigir el auto.
* Turbo (Boost): Abre la boca para activar el modo de alta velocidad y cambiar el color del entorno a rojo neón.

Créditos
Desarrollado como actividad práctica para la materia de Programación de Entornos Virtuales.
