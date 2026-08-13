# Herramienta para Extracción y Análisis de Fragmentos Resaltados en Documentos .docx

Proyecto desarrollado como parte de mi aprendizaje inicial de programación. Durante el desarrollo se utilizaron herramientas de IA como recurso de consulta para familiarizarme con la biblioteca empleada, comprender su documentación y resolver problemas puntuales de implementación.

Este repositorio contiene un notebook de Python (.ipynb) diseñado para automatizar la extracción de fragmentos resaltados y sus colores de resaltado en documentos .docx. El código accede al XML subyacente del archivo, identifica los fragmentos de texto destacados y extrae sus colores en formato hexadecimal. Estos colores son luego interpretados según un diccionario predefinido que los clasifica en tipos específicos de intervención textual (por ejemplo, REEMPLAZO, ADICIÓN, etc.).

El propósito de esta herramienta es facilitar el análisis de transformaciones textuales en múltiples versiones de un mismo documento, un proceso central en mi tesina de investigación. Además, el notebook agiliza la tarea de identificar y clasificar intervenciones textuales en una gran cantidad de fragmentos, reduciendo el trabajo manual y facilitando la posterior revisión de los datos.

### Características:
- Extrae fragmentos resaltados y sus colores de documentos `.docx`.
- Clasifica intervenciones textuales según un diccionario de colores.
- Facilita la revisión de múltiples versiones de un mismo texto.

El código está disponible para ser usado, modificado y adaptado según distintas necesidades. Ten en cuenta que no se incluyen los textos utilizados en la tesina por razones académicas y de privacidad.

### Uso:
1. Descarga el archivo `.docx` que desees analizar.
2. Ejecuta el notebook para extraer los datos resaltados y sus colores.
3. Revisa los resultados y ajusta el diccionario de colores según sea necesario.


