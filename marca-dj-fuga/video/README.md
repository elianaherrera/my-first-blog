# Pieza animada

Presentación del logotipo en movimiento. Dura **5,4 segundos a 60 fps**.

## El guion

| Tiempo | Qué pasa |
|---|---|
| 0,0 – 0,6 | Una línea magenta barre el cuadro y deja las letras a su paso. |
| 0,2 – 1,3 | F, U, G y A suben desde la línea de base, escalonadas. |
| 1,6 – 2,2 | **La G gira.** Entra derecha y se da vuelta en pantalla. |
| 2,1 – 2,7 | Los filetes se abren desde el centro hacia afuera. |
| 2,3 – 2,8 | Baja el DJ. |
| 2,6 – 3,0 | Estalla el destello y cierra la pieza. |
| 3,0 – 5,4 | Reposo, con una respiración apenas perceptible. |

La decisión de fondo: **la palabra se arma con la G derecha y recién después gira.**
Si la G entrara ya espejada, el logo sería una rareza gráfica. Al girar en pantalla, el
espectador ve el concepto ocurrir en lugar de que se lo expliquen.

## Qué archivo usar

| Dónde | Archivo |
|---|---|
| Feed de Instagram, carrusel, post cuadrado | `dj-fuga-animacion-1x1.mp4` |
| Lo mismo, sobre el fondo azul | `dj-fuga-animacion-1x1-azul.mp4` |
| Stories, Reels, TikTok | `dj-fuga-animacion-9x16.mp4` |
| YouTube, pantalla de boliche, intro de set | `dj-fuga-animacion-16x9.mp4` |
| Superponer sobre un video (edición) | `dj-fuga-animacion-alfa.mov` |
| Superponer en una web | `dj-fuga-animacion-alfa.webm` |

Los dos últimos tienen **canal alfa**: el fondo es transparente, así que el logo se
apoya sobre cualquier imagen. El `.mov` abre en Premiere, After Effects, CapCut, DaVinci
y Final Cut; el `.webm` sirve para web.

## Sin música

La pieza va muda a propósito. El corte del destello (segundo 2,6) está pensado para
caer sobre un golpe: si se le monta un tema, conviene alinear ahí el kick o el drop.
Usar solo música con licencia; un audio reclamado silencia el posteo entero.

## Volver a renderizar

`fuente/animacion.html` es el original. Abre en cualquier navegador y se reproduce sola.
Acepta parámetros por URL: `?w=1080&h=1920` fija el encuadre, `&alpha=1` saca el fondo,
`&still=1` la congela para poder recorrerla cuadro por cuadro con `window.__seek(segundos)`.

Las letras están convertidas a curvas dentro del propio archivo: no depende de tener
ninguna tipografía instalada.

Acepta también `&fondo=azul`, que es como se generó la variante sobre Azul Cabina.

## Paleta en movimiento

El único color de la pieza es el **magenta** (`#FF2E86`): aparece en la línea que barre
el cuadro al principio y en la estela que sigue a la G cuando gira. Nada más. El resto
es blanco sobre el fondo, negro o azul. Es la misma regla que el manual: el magenta es
detalle, no fondo.
