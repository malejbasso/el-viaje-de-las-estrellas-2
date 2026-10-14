# El viaje de las estrellas

Libro web interactivo basado en el relato de la Escuela Los Lirios.

## Publicar en GitHub Pages

1. Sube todo el contenido de esta carpeta a la raíz del repositorio.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Elige la rama `main`, la carpeta `/ (root)` y guarda.

También puedes probarlo abriendo `index.html` directamente. No requiere instalación ni conexión a internet.

La experiencia comienza con un libro de cuero azul cerrado sobre una mesa antigua. Al pulsar **Abrir el libro**, una transición cinematográfica acerca la cámara y revela el libro abierto. Desde ese momento se habilita la navegación por las páginas.

## Controles

- Botones laterales inferiores.
- Flechas izquierda y derecha del teclado.
- Clic en la mitad izquierda o derecha del libro.
- Deslizamiento horizontal en pantallas táctiles.
- Botón **Pantalla completa** para ampliar la experiencia.
- Botón **Salir de pantalla completa** o tecla `Esc` para volver a la ventana normal.
- Botón **Reiniciar** para regresar a la portada.
- Botón **Modo proyección / Vista normal** para adaptar el libro cuando un objeto físico cubre el sector derecho de la pantalla.

## Modo proyección

Esta versión abre por defecto en un modo especial para escenarios donde el sector derecho de la proyección está obstruido. El libro conserva las dos hojas y el efecto 3D, pero ocupa menos ancho y se alinea dentro del 72 % izquierdo de la pantalla. La selección queda guardada en el navegador.

En este modo, el clic se calcula respecto del centro real del libro desplazado: la hoja izquierda retrocede y la hoja derecha avanza. Los controles superiores cuentan con espacios independientes para evitar superposiciones.

Para una presentación sin obstáculos, pulsa **Vista normal**. En teléfonos, el libro continúa usando automáticamente una sola hoja y ocupa el centro de la pantalla.

## Archivos

- `index.html`: contenido, diseño y animaciones.
- `assets/`: ilustraciones cinematográficas.
