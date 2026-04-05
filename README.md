# swim-game-ia
Swim Game IA - Estilo Tomasin Pinguin 🐧🏊‍♂️

¡Bienvenido al código fuente del minijuego interactivo "Swim Game"!
Este proyecto fue creado para ser parte de un tutorial para el canal de YouTube Tomasin Pinguin, donde demostraré cómo controlar un videojuego en el navegador utilizando Inteligencia Artificial (específicamente la detección facial) usando tu propia cámara web (Video proximamente a ser grabado).

🎮 Juega ahora

Puedes jugar directamente en tu navegador sin instalar nada haciendo clic en el siguiente enlace:
👉 JUGAR SWIM GAME IA https://tomasinpinguin.github.io/swim-game-ia/

🔒 Aviso de Privacidad (Disclaimer sobre la Cámara)

¡Tu privacidad es lo más importante! Este juego solicita acceso a tu cámara web única y exclusivamente para controlar el movimiento del personaje en pantalla en tiempo real.

No se graban videos ni se toman fotos.
No se almacena ninguna información facial.
No se envían datos a ningún servidor externo.
Todo el procesamiento de Inteligencia Artificial (reconocimiento de la posición de la nariz) ocurre localmente en tu propio navegador. Una vez que cierras la página, el acceso a la cámara termina. ¡Puedes jugar con total seguridad!

🛠️ Tecnologías utilizadas

Este proyecto está construido 100% con tecnologías web, sin necesidad de servidores adicionales:

HTML5 & JavaScript - La estructura y lógica principal.

p5.js - Biblioteca de JavaScript para la creación de gráficos, animaciones y el manejo del canvas (incluyendo shaders WebGL).
ml5.js - Biblioteca amigable de Machine Learning para la web. Utilizamos el modelo FaceMesh para detectar la punta de la nariz del jugador.
GLSL (Shaders) - Para generar el efecto animado y distorsionado del agua en el fondo.

📂 ¿Cómo ejecutarlo localmente?

Dado que todo el código está unificado en un solo archivo, es muy fácil probarlo o modificarlo en tu computadora:
- Descarga el archivo index.html de este repositorio.
- Haz doble clic en el archivo para abrirlo en tu navegador web favorito (Chrome, Firefox, Safari, Edge).
- Concede el permiso de uso de la cámara cuando el navegador lo solicite.

¡Diviértete modificando el código para cambiar los colores, la velocidad o el personaje!

🤝 Contribuciones

Si quieres mejorar el juego, añadir sonidos, cambiar las mecánicas o corregir algún error de la IA, ¡siéntete libre de hacer un Fork de este repositorio y enviar tus Pull Requests!

Creado con fines educativos y de diversión. ¡Qué lo disfrutes!
