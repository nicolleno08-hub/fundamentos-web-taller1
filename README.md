# fundamentos-web-taller1

## Verificación de código

### Caso A
* **Problema identificado:** La etiqueta `<img>` utilizaba el atributo `href` para referenciar la imagen, lo cual es incorrecto.
* **Corrección realizada:** Se cambio `href` por el atributo estándar `src` (`<img src="multimedia/perfil.jpg" alt="...">`).
* **Fuente consultada:** MDN Web Docs - HTML Image Element (`<img>`).

### Caso B
* **Problema identificado:** La etiqueta de enlace `<a>` utilizaba `src` en lugar de `href`.
* **Corrección realizada:** Se reemplazó por `<a href="https://developer.mozilla.org/">Consultar MDN</a>`.
* **Fuente consultada:** MDN Web Docs - HTML Anchor Element (`<a>`).

### Caso C
* **Problema identificado:** El elemento `<source>` dentro del reproductor de video empleaba `href`.
* **Corrección realizada:** Se actualizó a `<source src="multimedia/video.mp4" type="video/mp4">`.
* **Fuente consultada:** MDN Web Docs - HTML Media Source Element (`<source>`).

### Caso D
* **Problema identificado:** El atributo `type="correo"` no existe en la especificación estándar de HTML5.
* **Corrección realizada:** Se modificó por `type="email"`, permitiendo la validación nativa de direcciones de correo electrónico.
* **Fuente consultada:** MDN Web Docs - HTML Input Element (`<input type="email">`).

### Caso E
* **La afirmación es:** Falsa.
* **Justificación:** HTML5 no reconoce la etiqueta `<image>` como estándar para insertar imágenes, ni requiere cierre `</image>`. La etiqueta correcta es `<img>`, la cual es una etiqueta vacía (sin etiqueta de cierre).
* **Fuente consultada:** MDN Web Docs - HTML Specification (`<img>`).