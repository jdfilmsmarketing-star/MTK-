# Check-in de Equipos

App para revisar que todo el equipo esté en la mochila antes de salir a grabar una cobertura.
Tocas cada equipo cuando lo metes en la mochila, y la app te dice qué falta. Así no se te queda nada.

## La lista

**Cámara**
- Cámara
- Baterías de la cámara
- Lentes
- Filtros

**Sonido**
- Micrófonos
- Cables del micrófono

**Trípode y estabilizador**
- Trípode
- Piececita (lo que agarra la cámara al trípode)
- Estabilizador
- Mango del estabilizador
- Base del estabilizador

**Luces y baterías**
- Luces
- Baterías

## Cómo se usa

1. Escribe qué vas a grabar en **Cobertura** (ej. boda, entrevista). No es obligatorio.
2. Toca cada equipo cuando lo metas en la mochila. Se pone verde.
3. Arriba, la batería se va llenando y te dice cuántos faltan. Si tocas el nombre de algo que falta, la app te lleva a ese equipo en la lista.
4. Cuando está todo, dice **Todo en la mochila**.
5. Al terminar la cobertura, toca **Nueva cobertura** para desmarcar todo y empezar de cero.

Con **Editar lista** puedes cambiar nombres, quitar equipos que no uses o agregar equipos nuevos
(por ejemplo, memorias SD). Si te equivocas, **Volver a la lista original** deja los 13 de siempre.

Lo que marcas se guarda solo. Si cierras la app y la vuelves a abrir, sigue igual.

## Ponerla en el teléfono

La app es una página web (`index.html`). Para tenerla como app en el teléfono:

1. Publícala con GitHub Pages: en el repositorio ve a **Settings → Pages**, en **Source** elige
   **Deploy from a branch**, escoge la rama y la carpeta `/ (root)`, y guarda.
   GitHub te da un enlace como `https://<tu-usuario>.github.io/<repo>/`.
2. Abre ese enlace en el teléfono.
   - **iPhone (Safari):** botón de compartir → **Agregar a inicio**.
   - **Android (Chrome):** menú ⋮ → **Instalar app** o **Agregar a la pantalla principal**.

Después de abrirla una vez, funciona aunque no haya señal.

## Archivos

- `index.html`: la app completa.
- `manifest.webmanifest` y `icons/`: nombre e ícono cuando la instalas en el teléfono.
- `sw.js`: guarda la app en el teléfono para que abra sin internet.
