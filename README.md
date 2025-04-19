# Herramienta para Extracción y Análisis de Fragmentos Resaltados en Documentos .docx

Este repositorio contiene un script en Python diseñado para automatizar la extracción de fragmentos resaltados y sus colores de fondo en documentos `.docx`. El código accede al XML subyacente del archivo, identifica los fragmentos de texto destacados y extrae sus colores en formato hexadecimal. Estos colores son luego interpretados según un diccionario predefinido que los clasifica en tipos específicos de intervención textual (por ejemplo, **REEMPLAZO**, **ADICIÓN**, etc.).

El propósito de esta herramienta es facilitar el análisis de transformaciones textuales en múltiples versiones de un mismo documento, un proceso central en mi tesina de investigación. Además, el script agiliza la tarea de identificar y clasificar intervenciones textuales en una gran cantidad de fragmentos, mejorando la eficiencia del trabajo sin dejar de lado la revisión manual para garantizar la precisión de los datos.

### Características:
- Extrae fragmentos resaltados y sus colores de documentos `.docx`.
- Clasifica intervenciones textuales según un diccionario de colores.
- Facilita la revisión de múltiples versiones de un mismo texto.
- Herramienta de aprendizaje para trabajar con XML y técnicas de procesamiento de texto.

El código está disponible para ser usado, modificado y adaptado según las necesidades de quien lo necesite. Ten en cuenta que no se incluyen los textos utilizados en la tesina por razones académicas y de privacidad.

### Requisitos:
- Python 3.x
- Librerías: `python-docx`, `xml.etree.ElementTree` (u otras dependencias necesarias)

### Uso:
1. Descarga el archivo `.docx` que desees analizar.
2. Ejecuta el script para extraer los datos resaltados y sus colores.
3. Revisa los resultados y ajusta el diccionario de colores según sea necesario.

Para más detalles y contribuciones, revisa los archivos y la documentación proporcionada.
