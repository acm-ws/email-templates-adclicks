# Templates de email

Reemplazar contenido estático por las variables que use el equipo, no borren etiquetas o estilos:

- Nombre: texto en `sender-name` o `workspace-name`.
- Contenido: texto del párrafo `body-copy`.
- Fecha: texto del párrafo `metadata`, después de su etiqueta.
- Botón: texto en `button-label` y URL en `href`, en ambas versiones del botón (Outlook y estándar).
- Imágenes: URL en `src`; fondo en `background` y `background-image`. Preferencias y baja: URL en `href`.
- Resumen de bandeja: preheader oculto al inicio de `body`; título del documento en `title`.

Ejemplo: sustituir únicamente `Daniel Alvarado` dentro de `<span class="sender-name">Daniel Alvarado</span>`. El estilo se hereda del título y permanece igual para contenido equivalente. Textos más largos pueden ocupar más líneas.

Escapar valores como texto/atributos HTML desde el backend. Enlaces `example.com` son de muestra: reemplazarlos antes de enviar.

Ancho máximo: 750 px. Se mantienen estilos inline, adaptación móvil y markup de Outlook. Validación en clientes de correo mediante envíos reales sigue pendiente.
