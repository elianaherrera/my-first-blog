# DJ FUGA — Sistema de identidad visual

Identidad para un DJ emergente de 17 años. Música electrónica, comercial y club.

---

## 1. El concepto

**La G espejada es la marca.**

"Fuga" es escaparse, salirse del molde, irse para otro lado. El logo dice exactamente
eso con un solo gesto: todas las letras avanzan hacia adelante y **la G se da vuelta**.
Es la letra que se fuga.

Es un recurso que funciona en tres niveles a la vez:

- **Conceptual:** la marca significa lo que hace. No hace falta explicarlo.
- **Visual:** rompe la simetría de la palabra y genera un punto de tensión que el ojo
  busca. Eso es lo que hace que un logo se recuerde.
- **Práctico:** la G sola, fuera de la palabra, ya es un símbolo reconocible. Sirve de
  avatar, de sticker y de bordado sin tener que achicar el nombre completo.

A los 17 años el activo más valioso no es el logo: es el tiempo de repetición por
delante. Por eso el sistema está construido para que **aguante crecer** — del flyer de
boliche al line-up de un festival — sin tener que rehacerse.

---

## 2. Por qué esta dirección y no la otra

De las dos referencias que me pasaste elegí trabajar sobre la de **B.ROSE®**
(logo blanco, tipografía gruesa, sistema limpio) y no sobre el flyer rosa de Invincible.

El motivo es concreto: el flyer de Invincible **es un flyer**, no una marca. Resuelve
una noche. Esa estética —degradés, texturas, rosa saturado, Y2K— tiene fecha de
vencimiento corta y envejece rápido justo en los años en los que él va a estar
construyendo nombre.

La lógica de B.ROSE es la contraria y es la que necesita un artista que recién arranca:
un logo sólido en blanco y negro que **se apoya sobre la foto** en lugar de competir
con ella. Las fotos de cabina cambian todas las semanas; el logo no. Así cada posteo
suma a la misma marca en vez de empezar de cero.

**El rosa no se pierde: pasa a ser acento.** Está en la paleta como *Magenta Pulso*,
para flyers, stories y merch. Lo que cambia es la jerarquía: la marca es el blanco y
negro, el color es la temporada.

---

## 3. Las piezas del sistema

| Pieza | Cuándo se usa |
|---|---|
| **Logotipo principal** (apilado, con destello y bajada "DJ") | Portadas, afiches, merch, presentaciones. Es la versión completa. |
| **Logotipo horizontal** (`DJ FUGA` en una línea) | Headers, banners, firmas de mail, line-ups, cualquier espacio ancho y bajo. |
| **Isotipo** (la G espejada sola) | Avatares, stickers, bordados, favicon, marca de agua, cualquier espacio cuadrado. |
| **Sello `FUGA`** (destello + palabra) | Tamaños chicos, etiquetas de merch, sellos sobre foto. |
| **Cápsula** (`DJ FUGA` dentro de una píldora, sólida o en contorno) | Stickers, etiquetas de merch, sello sobre foto. Es la pieza más resistente del sistema: se sigue leyendo a 40 px. |
| **Contorno** | Para apoyar sobre fotos y video sin tapar la imagen. |

---

## 4. Paleta

| Color | Hex | Rol |
|---|---|---|
| **Negro Fuga** | `#0C0C0E` | Color base de la marca. No es negro puro: tiene un punto de azul que lo hace menos duro en pantalla. |
| **Blanco Flash** | `#F5F4F0` | Logo sobre fondo oscuro. Blanco cálido, no clínico. |
| **Magenta Pulso** | `#FF2E7E` | Acento de noche y de club. Detalles, titulares, fondos de flyer. |
| **Lima Señal** | `#D7FF4F` | Acento secundario. Para contrastar con el magenta en drops, merch o temporadas. |

**Regla de uso:** el 80% de la comunicación va en blanco y negro. El color entra como
acento, no como fondo por defecto. Si todo es rosa, el rosa deja de significar algo.

Los dos acentos **nunca se usan juntos en la misma pieza** salvo que sean la idea
central de la campaña.

---

## 5. Tipografía

| Uso | Fuente | Pesos |
|---|---|---|
| Logo y títulos | **Unbounded** | 900 / 700 |
| Textos, fechas, line-ups, bajadas | **Space Grotesk** | 500 / 700 |

Las dos son gratuitas y de uso comercial libre (SIL Open Font License), y están en
Google Fonts. Se descargan en `fonts.google.com`.

> El logo ya viene con las letras convertidas a curvas: los archivos de esta carpeta
> **no dependen de tener la fuente instalada**. La fuente hace falta solo para escribir
> textos nuevos (fechas, nombres de fiestas, line-ups).

---

## 6. Reglas de uso

**Área de resguardo.** Dejar libre alrededor del logo, como mínimo, el ancho de la
letra F. Nada entra ahí: ni texto, ni bordes, ni otro logo.

**Tamaños mínimos.**

| Versión | Mínimo en pantalla | Mínimo impreso |
|---|---|---|
| Logotipo principal | 180 px de ancho | 35 mm |
| Logotipo horizontal | 220 px de ancho | 45 mm |
| Isotipo | 32 px | 10 mm |

Por debajo del mínimo del principal, usar el **horizontal**. Por debajo del horizontal,
usar el **isotipo** solo.

**Lo que no se hace:**

- No enderezar la G. Es el logo, no un error.
- No estirar ni comprimir: escalar siempre proporcional.
- No cambiar el espaciado entre letras. El aire entre la U y la G está calculado para
  que la barra de la G no se pegue a la U.
- No ponerle sombra, degradé, contorno doble ni efecto 3D.
- No usarlo en colores fuera de la paleta.
- No apoyarlo sobre una foto clara o cargada sin usar la versión contorno, o sin bajarle
  el brillo a la imagen.
- No rehacer el logotipo escribiéndolo con la fuente: usar siempre estos archivos.

---

## 7. Sobre el símbolo ®

El `®` **no se usa** hasta que el nombre esté efectivamente registrado como marca
(en Argentina, ante el INPI). Usarlo antes es incorrecto.

Mientras tanto, si se quiere el gesto gráfico, el símbolo correcto es `™`, que no
requiere registro previo.

---

## 8. Archivos

```
marca-dj-fuga/
├── svg/   vectores — escalan a cualquier tamaño sin perder calidad
└── png/   mapas de bits con fondo transparente, listos para usar
```

**Qué archivo agarrar según el caso:**

| Necesito… | Archivo |
|---|---|
| Foto de perfil de Instagram / Spotify / SoundCloud | `png/dj-fuga-avatar-negro-1080.png` |
| Logo sobre fondo oscuro | `svg/logotipo-principal-blanco.svg` |
| Logo sobre fondo claro | `svg/logotipo-principal-negro.svg` |
| Imprenta, merch, bordado, vinilo de corte | cualquier archivo de `svg/` |
| Pegarlo arriba de una foto | `svg/contorno-blanco.svg` |
| Stickers, etiquetas de merch, sello | `svg/capsula-solida-blanco.svg` |
| Mandárselo a un productor o a un boliche | `png/dj-fuga-horizontal-blanco.png` |

Los `.svg` son el **original**. Siempre que se pueda, usar esos: no pierden calidad
nunca y cualquier imprenta los puede abrir.
