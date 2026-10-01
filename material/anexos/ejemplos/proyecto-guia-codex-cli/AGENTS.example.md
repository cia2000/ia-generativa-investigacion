# Instrucciones del proyecto

## Fuentes de verdad

- Considera los documentos del directorio `docs/` como la fuente de verdad del proyecto.
- No inventes, completes ni contradigas información que no esté respaldada por esos documentos o por una fuente externa verificable.

## Documentación generada

- Guarda toda la documentación generada en el directorio `gen/`.
- Por cada documento creado o actualizado en `gen/`, crea o actualiza su copia en inglés en el directorio `gen-en/`.
- Conserva la estructura de nombres y carpetas entre `gen/` y `gen-en/` para que cada documento tenga una correspondencia inequívoca.

## Registro de documentos

- Mantén actualizado el archivo `docs-guide.md`, situado en la raíz del proyecto, cada vez que crees o modifiques un documento de `gen/`.
- Para cada documento de `gen/`, registra en `docs-guide.md` su ruta, la fecha y hora de la última actualización y su versión actual.
- Usa el patrón `v-<numero de actualización>` para las versiones, por ejemplo, `v-1`, `v-2` y `v-3`.
- Incrementa el número de versión cuando modifiques el contenido del documento correspondiente.

## Bibliografía y fuentes

- Registra en `bibliografia.md` cada fuente consultada para elaborar o modificar la documentación del proyecto.
- Incluye, cuando esté disponible, autoría, título, fecha de publicación, enlace y fecha de consulta.
- No presentes como verificadas fuentes que no hayas podido consultar.
