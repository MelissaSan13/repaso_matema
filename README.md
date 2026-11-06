# Guía de repaso: Matemáticas y Física (10.º y 11.º)

Sitio web estático, adaptable a celulares y computadores, con los diez temas, ejemplos resueltos, 50 ejercicios, diagramas SVG, un cuestionario interactivo, lista de autoevaluación y enlaces a simulaciones educativas.

## Publicar con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo, `guia-matematicas-fisica`).
2. Sube el archivo `index.html` a la raíz del repositorio.
3. Entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub genere la dirección pública del sitio. Será similar a:
   `https://TU-USUARIO.github.io/guia-matematicas-fisica/`

## Archivos

- `index.html`: página completa. No requiere instalar programas, frameworks ni dependencias.

## Personalización

- Cambia el título, descripción o nombre del colegio directamente en `index.html`.
- Los diagramas están dibujados en SVG dentro del archivo, por lo que no dependen de imágenes externas.
- El cuestionario y la autoevaluación funcionan con JavaScript integrado.
- Los enlaces a PhET y GeoGebra requieren conexión a internet.
