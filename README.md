# Lanza31 — Panel del Lanzamiento (Círculo de Importadores)

Panel web del lanzamiento: recaudo en pesos y dólares, meta/ROAS, no registrados (para llamar y registrar) y registrados.

## Archivos
- **`index.html`** — el panel completo. Es **autocontenido** (los datos van dentro del archivo, no necesita internet ni servidor). Ábrelo con doble clic o súbelo a cualquier hosting.

## Subirlo a GitHub Pages
1. Crea un repositorio nuevo en GitHub (ej. `lanza31`).
2. Sube el archivo `index.html` (arrástralo en *Add file → Upload files*, o `git push`).
3. Ve a **Settings → Pages → Build and deployment**, en *Source* elige **Deploy from a branch**, rama `main` y carpeta `/root`. Guarda.
4. En ~1 minuto queda publicado en `https://TU-USUARIO.github.io/lanza31/`.

## Cómo se actualiza
- El panel **no lee solo** el documento de Hotmart (por seguridad, una página estática no accede a tu Drive).
- Flujo: le pasas a Claude el **nuevo export de Hotmart** → Claude regenera este `index.html` → reemplazas el archivo en GitHub → la página muestra los datos nuevos (dale al botón **🔄 Actualizar**).
- Lo que marques (✔ Llamado, ✔ Registrado), las notas, la TRM, la meta y la pestaña activa se **guardan en tu navegador** y se conservan aunque actualices los datos.

## Notas de datos
- **HotMart** se toma en su moneda real; **Bancolombia/Davivienda** siempre en COP.
- La columna USD de tu `Sales Records` viene incompleta: para HotMart se usa el export de Hotmart (moneda correcta).
- Periodo: **del 30/07/2026 en adelante**.
