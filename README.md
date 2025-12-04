# IA-Scraping-Lab

Este repositorio sirve como prueba práctica sobre la propuesta de uso del archivo `llms.txt`, un formato emergente que se quiere implementar para que los crawlers de IA puedan recoger información de manera estructurada y controlada.

## Propósito

El objetivo es demostrar dos caras del archivo `llms.txt`:

- **Uso legítimo**: El archivo puede usarse para facilitar la recogida de información de la página web, estructurando los datos en formato Markdown para que los crawlers IA los interpreten fácilmente y respeten las reglas establecidas.
- **Uso manipulado o creativo**: El archivo también puede usarse para mostrar información totalmente diferente a la de la página web, demostrando cómo se podría realizar una "trampa" o manipulación. En nuestro ejemplo, la página web es una cafetería, pero el archivo `llms.txt` contiene información sobre un kebab alemán, sin relación alguna con la web.

## Contenido del repositorio

- `index.html`: Página web de la cafetería, creada en HTML.
- `llms.txt`: Archivo de ejemplo, redactado en alemán, que muestra la dualidad de usos.

## Ejemplo práctico

### Uso legítimo

El archivo `llms.txt` puede contener instrucciones y datos estructurados relacionados con la página web, facilitando la recogida de información de forma ética y organizada.

### Uso manipulado

En este ejemplo, el archivo `llms.txt` contiene información sobre un kebab alemán, mientras que la página web trata de una cafetería. Esto demuestra cómo se podría manipular la información que reciben los crawlers IA, mostrando datos diferentes a los de la página principal.

## Instrucciones de uso

- Sube los archivos `index.html` y `llms.txt` a tu repositorio.
- Si usas GitHub Pages, la web estará disponible en la raíz y los crawlers podrán consultar automáticamente `/llms.txt`.
- Puedes modificar el contenido de `llms.txt` para probar ambos usos: legítimo y manipulado, y verificar cómo los crawlers IA interpretan la información.
