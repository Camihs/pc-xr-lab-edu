# NEXUS PC LAB

**Laboratorio interactivo de hardware, electrónica y PC gaming.**

NEXUS PC LAB es una experiencia web educativa e interactiva para explorar componentes de computadores y equipos PC Gamer en 3D, comprender sus funciones y aprender criterios básicos de compatibilidad eléctrica y de hardware.

## Experiencias

- **Biblioteca 3D:** torre PC Gamer, mini PC, CPU con refrigeración, memoria RAM DDR5, motherboard ATX, GPU dedicada, SSD NVMe M.2 y portátil gaming.
- **Exploración 3D:** rotación, zoom, encuadre, pantalla completa y carga de modelos GLB/GLTF propios.
- **Realidad aumentada:** activación en dispositivos y navegadores compatibles.
- **Laboratorio VR:** escena inmersiva WebXR con el modelo seleccionado.
- **PC Build Studio:** configurador educativo de CPU, motherboard, GPU, RAM, almacenamiento, refrigeración y fuente, con revisión de socket y estimación de consumo.
- **Centro de aprendizaje:** retos, puntos de interés, atribución de modelos, ficha descargable, narración y generador local de prompts pedagógicos.

## Tecnologías

- HTML5, CSS3 y JavaScript ES6+
- Google model-viewer 4.1.0
- A-Frame 1.8.0 / WebXR
- Web Speech API
- File API y Object URLs

No requiere backend, base de datos ni claves API. Los modelos 3D de la biblioteca se sirven desde sus fuentes externas; la carga de modelos propios se realiza localmente en el navegador.

## Ejecutar

Abre `index.html` en un navegador moderno o publica el repositorio en Vercel / GitHub Pages. Para RA y WebXR se requiere HTTPS y un dispositivo compatible.

## Equipo desarrollador

- Andres Santiago Rangel De La Cruz
- Jorge Daniel Bordeth Jimenez
- Fredy Andres Machado Manjarres
- Sebastian David Mendoza Orozco

## Créditos de modelos

Los modelos de la biblioteca inicial están atribuidos a Innerscene (CC0), según las referencias de origen incorporadas en la aplicación. Si se añaden modelos de terceros, conserva siempre su licencia y atribución correspondiente.
