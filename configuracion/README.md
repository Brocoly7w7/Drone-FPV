# Exportar configuración de Betaflight

La configuración de vuelo de este dron fue realizada en **Betaflight**; no se ha proporcionado aún un respaldo real. Este directorio solo documenta cómo conservarlo.

## Obtener un respaldo de lectura

1. Retira las hélices antes de conectar el dron para configuración o pruebas en el escritorio.
2. Conecta la controladora al equipo mediante USB y abre **Betaflight Configurator**.
3. Conéctate a la controladora y entra en la pestaña **CLI**.
4. Escribe `diff all` y presiona Enter. El comando **muestra** la configuración relevante; no modifica la controladora.
5. Utiliza **Save to File** si tu versión de Configurator muestra esa opción, o copia el resultado a un archivo `.txt`.
6. Conserva una copia privada íntegra. **Antes de publicar otra copia**, revisa si incluye identificadores de receptores, frases de enlace, configuraciones personales u otros valores que no deseas divulgar.
7. Registra versión del firmware y modelo exacto de la controladora junto al respaldo si puedes confirmarlos.

**Importante:** no pegues una configuración `diff` o `dump` de una versión de Betaflight en otra versión/placa. Se trata de documentación, no de instrucciones para restaurar sin comprobación.

Guía oficial: [Betaflight — Setup Guide](https://betaflight.com/docs/wiki/getting-started/setup-guide)
