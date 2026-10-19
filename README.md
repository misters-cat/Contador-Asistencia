# Contador de asistencia

Aplicación HTML estática para registrar asistentes por sector en reuniones. **No necesita base de datos**.

## Características
- Tipos de reunión: entre semana (azul) y fin de semana (morado).
- Fecha editable.
- Plataforma, Izquierda, Centro, Derecha, Fondo, Literatura, Hall, Estacionamiento, Otros y Zoom.
- Entrada manual y botones +/− por sector.
- Suma automática del presencial, Zoom y total general.
- Compartir por WhatsApp el resumen con o sin detalle; copiar resumen.
- Guardado local en el navegador, con botón para reiniciar el conteo.

## Publicar gratis en GitHub Pages

1. Crear un repositorio **público** llamado `Contador-Asistencia`.
2. Subir `index.html` a la raíz de la rama `main` (este proyecto no necesita instalaciones, compilación ni dependencias).
3. En **Settings → Pages → Build and deployment**, elegir **Deploy from a branch**.
4. Seleccionar la rama **main** y carpeta **/(root)**, y guardar.
5. La dirección del sitio será `https://misters-cat.github.io/Contador-Asistencia/` si el repositorio se creó con el usuario de GitHub `misters-cat`.

**Importante:** cada dispositivo conserva sus cantidades localmente; no se comparten entre usuarios. La aplicación genera el mensaje de WhatsApp desde los valores que se ingresen.

Para modificarla en el futuro, edita `index.html` en GitHub y confirma el cambio en `main`. GitHub Pages publicará automáticamente la nueva versión.