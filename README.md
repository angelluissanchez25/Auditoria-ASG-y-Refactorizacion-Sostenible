# Auditoria-ASG-y-Refactorizacion-Sostenible

Fase 1: Inventario y Dimensión Ambiental (A)

<img src="img/Captura de pantalla 2026-05-19 111441.png" alt="Captura.png">

En esta captura se puede apreciar que nuestra empresa, Boafit, tiene un peso de 0,26 g de C02. Esta huella de carbono está mejor que la media de las páginas de internet.


Los 3 elementos más pesados de la página web son:

Para empezar una cosa que está mal son las imágenes, no están bien optimizadas lo normal es que las imágenes esten en .jpg sin embargo algunas de las imágenes de la página web están en formato de texto o html. Esto provoca mucho más consumo de lo necesario.

Las librerías de javascript. La página tiene que cargar muchos JS a la vez. Esto son las animaciones de subir y bajar en la página. Es algo que está guay y da un toque moderno pero consume mucha memoria.

Por último. Los CSS, debido a las capas de la página, esta se ve obligada a cargar muchas hojas de estilo. Lo que provoca lentitud en la página.

Boafit es exactamente lo que llamamos inflación de software. Gracias a la modernización y a wordpress el diseño de las páginas web se ha vuelto algo muy fácil de hacer, pero se hace mal, no se suele mirar el consumo de la pagina, solo si esta guay y llama la atención.
Fase 2: Dimensión Social y Equidad (S)
Usando la herramienta WAVE Web Accessibility Evaluation Tool, podemos ver un problema en los textos sobre imágenes sin capas de contraste, esto dificulta la lectura de ellas bajo la luz solar, o con problemas de vista.

Otro problema es que muchas imágenes o banners promocionales no tienen atributo alt, esto es un problema para personas con diversidad funcional visual que utilizan lectores de pantalla, ya que el software no puede describir el contenido de la imagen.
Fase 3: Dimensión de Gobernanza y Ética (G)

En la página de Boafit no es obligatorio aceptar las cookies, las cookies sirven para guardar la información de esa página, por ejemplo si aceptas las cookies de amazon se guardará el historial de búsqueda y el carrito a la vez que te recomendará cosas que ya hayas buscado o comprado por si te interesan.

Si quieres registrarte en la página de Boafit solo te pedirá un email y una contraseña, sin embargo, si te quieres registrar en el gimnasio como tal, sí que se te pedirá el número de teléfono para la factura y el DNI.
Fase 4: Propuesta de Refactorización (Green Coding)

Para reducir el peso de la web y el consumo energético en la transmisión de datos es necesario sustituir todas las imágenes .jpg y .png por formatos como WebP o AVIF, esto reduce el peso de los archivos entre un 30%-50% sin pérdida de calidad.

Se puede implementar el atributo loading=”lazy” en todas las imágenes que no estén en el primer pantallazo, esto evita que el navegador descargue recursos que el usuario no vaya a ver.

Para mejorar la eficiencia de la página es necesario eliminar frameworks viejos, fuentes de Google redundantes, plugins de redes sociales y scripts de analítica duplicados, pasar a iconos SVG en lugar de librerías enteras.

Que los scripts de chats en vivo, herramientas de comentarios y anuncios solo se carguen cuando el usuario interactúe o haga scroll.

Para evitar que el éxito anule el ahorro se debe hacer una serie de cambios

Hosting Verde: Alojar la web en servidores que utilicen energía 100% renovable.

Caché: Entrega páginas estáticas desde servidores cercanos al usuario para que la CPU del servidor central casi ni trabaje.

Peso: Mantener un presupuesto de peso estricto.

UX Directa y Modo Oscuro: Diseña para que el usuario encuentre lo que busca rápido (menos tiempo de pantalla) y ofrece modo oscuro para ahorrar batería.

