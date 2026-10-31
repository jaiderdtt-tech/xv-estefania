# Invitación XV años de Estefanía

Invitación digital: portada con foto, cuenta regresiva, mapa, pase personalizado y confirmación por WhatsApp.

## Subir a GitHub Pages

1. En GitHub crea un repositorio **público** llamado `xv-estefania`.
2. Entra al repositorio, toca **Add file > Upload files** y arrastra `index.html`, `README.md` y la carpeta `assets` completa. Toca **Commit changes**.
3. Ve a **Settings > Pages**. En *Source* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y guarda.
4. En uno o dos minutos la invitación queda en:
   `https://jaiderdtt-tech.github.io/xv-estefania/`

## Vista previa al compartir por WhatsApp

En `index.html`, busca la línea `og:image` y cambia `jaiderdtt-tech` por tu usuario de GitHub. Así, al pegar el enlace en WhatsApp aparece la foto con el nombre y la fecha (`assets/og.jpg`). WhatsApp guarda la vista previa en caché, así que pruébala después de hacer este cambio.

## Versiones por número de personas

| Archivo | Enlace | Pase para |
| --- | --- | --- |
| `index.html` | `https://jaiderdtt-tech.github.io/xv-estefania/` | 1 persona |
| `daysqd.html` | `https://jaiderdtt-tech.github.io/xv-estefania/daysqd.html` | 2 personas |
| `puge5h.html` | `https://jaiderdtt-tech.github.io/xv-estefania/puge5h.html` | 3 personas |
| `yx6w7t.html` | `https://jaiderdtt-tech.github.io/xv-estefania/yx6w7t.html` | 4 personas |
| `wufhw8.html` | `https://jaiderdtt-tech.github.io/xv-estefania/wufhw8.html` | 5 personas |

Cada invitado solo ve el número de su propio pase. Los nombres de los archivos son códigos al azar para que nadie pueda adivinar el enlace de otra versión, y el número de personas no se puede cambiar desde el enlace. Si alguien borra el código del enlace, llega a la versión de 1 persona.

Las confirmaciones llegan al WhatsApp 315 697 0185 e indican cuántas personas confirman. Si cambias algo en `index.html`, repite el cambio en los otros cuatro archivos: son copias iguales y solo cambia el número de personas.

## Nombre del invitado en el pase (opcional)

Puedes agregar al final de cualquier enlace el nombre del invitado:

```
https://jaiderdtt-tech.github.io/xv-estefania/yx6w7t.html?para=Familia%20Gómez
```

El nombre aparece en "Reservado para" y llena el campo de nombre al confirmar. Los espacios se escriben como `%20`.

## Datos que puedes editar

Todo está al inicio del `<script>` en `index.html`, en el bloque `DATOS`:

| Dato | Para qué sirve |
| --- | --- |
| `quinceanera` | Nombre que va en los mensajes de WhatsApp y el calendario |
| `inicio` / `fin` | Hora del evento (cuenta regresiva y calendario) |
| `whatsappConfirmacion` | Número que recibe las confirmaciones (con 57 adelante), hoy 315 697 0185 |
| `lugar` | Texto que busca el mapa. También acepta coordenadas copiadas de Google Maps, en formato `latitud,longitud` |
| `enlaceMaps` | Si pegas aquí el enlace exacto de Google Maps (Compartir > Copiar enlace), el botón lo usa |

El nombre grande de la portada está en la etiqueta `<h1 class="nombre">`.

## Cambiar la foto

La portada usa `assets/estefania.webp`: Estefanía con el vestido verde menta, sin fondo. Para usar otra foto, reemplaza `assets/estefania.webp` por una imagen con el mismo nombre. Funciona mejor con fondo transparente, en formato vertical (680 × 800 px aprox.) y con la persona centrada.

---
Invitación diseñada por Davinson, 311 835 7763.
