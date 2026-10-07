# DEXIAE — Archivos públicos que lee la aplicación

Este repositorio tiene dos archivos públicos que DEXIAE descarga. La aplicación
**sólo los lee**: no le envía nada a este repositorio.

## `lista.json`

- Las licencias dadas de baja, como **hashes SHA-256 de identificadores de
  equipo**: a partir de un hash no se puede saber a qué persona ni a qué equipo
  corresponde.
- La última versión publicada, para avisar en la aplicación que hay una nueva.

DEXIAE lo descarga al abrir, como mucho una vez cada 24 horas. Desde la versión
2.9.0, una licencia que figura como dada de baja pasa a **sólo lectura**: se ve
el Historial y se abren los Excels ya generados, pero no se procesa. De la
2.5.16 a la 2.8.0 sólo se muestra un aviso.

## `canal.json` (desde la versión 2.9.0)

«Novedades»: paquetes **firmados digitalmente** por DEXIAE (renovaciones de
licencia, plantillas, sets de reglas, configuraciones de clientes, diccionarios
del Asistente y avisos). Si la firma no coincide, la aplicación los ignora. Los
que van dirigidos a una licencia viajan **cifrados**: sin la clave de esa
licencia no se pueden leer.

## Uso

- **Sólo lectura** para todos.
- **Edición** restringida al equipo de DEXIAE.

## Contacto

contacto@getdexiae.com · https://getdexiae.com
