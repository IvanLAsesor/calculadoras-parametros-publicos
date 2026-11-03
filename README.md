# Parámetros públicos de las calculadoras

Este repositorio aloja exclusivamente parámetros públicos consumidos por calculadoras HTML que permanecen fuera de GitHub.

## Archivo central

- `parametros_maestros.json`: manifiesto JSON versionado.
- `schemaVersion`: versión del esquema que deben validar las calculadoras.
- `status: initial-baseline`: indica que los valores son una línea base heredada, no una actualización oficial recién comprobada.

## Privacidad

No subir aquí calculadoras con lógica privada, capturas de clientes, RFC, nombres, salarios ni expedientes. Las calculadoras deben enviar únicamente solicitudes de lectura para descargar este JSON; no deben enviar datos capturados.

## Estado de validación

Los valores de esta primera versión se trasladaron de las calculadoras existentes. Antes de considerarlos una actualización oficial automática, cada parámetro debe cotejarse con su publicación oficial y registrar fuente, fecha de publicación y vigencia. En particular, los valores ISSSTE de URV, pensión garantizada, cuota social y tope del Fondo de Pensiones requieren validación documental individual.

## Automatización

No se activa todavía ninguna tarea que sobrescriba parámetros. La automatización se incorporará después de verificar, para cada fuente, que la extracción es estable y que los datos superan validaciones. Un fallo de consulta nunca debe reemplazar el último paquete válido.
