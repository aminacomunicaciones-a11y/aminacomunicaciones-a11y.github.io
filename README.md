# aminacomunicaciones-a11y.github.io — portada del dominio

Portada de **Aminan**. Es el *sitio de usuario* de GitHub Pages: al llamarse el
repo exactamente igual que la cuenta, se publica en la **raíz** del dominio.

**En vivo:** https://aminacomunicaciones-a11y.github.io/

## Para qué existe

No es decorativo. Antes esta dirección devolvía el 404 de GitHub, y de ahí salían dos
cosas feas en los resultados de Google de **todo** el dominio:

| Problema | Causa | Lo arregla |
|---|---|---|
| El icono era el globo genérico | Google coge el favicon de la raíz del dominio | `/favicon.ico` con el icono del juego (desde el 6-sep-2026; antes, la A de Aminan) |
| Ponía «GitHub Pages documentation» | Google coge el nombre del sitio del título de la portada | El `<title>` de aquí: **Aminan** |
| El `robots.txt` no se leía | `robots.txt` solo vale en la raíz | El `robots.txt` de aquí, que declara los dos sitemaps |

> ⚠️ **El nombre de la marca es «Aminan», con N.** Las grafías sin la N son
> incorrectas. Pero **el dominio `aminacomunicaciones-a11y.github.io` sí lleva la
> grafía vieja y NO se toca**: es una dirección real y cambiarla rompe todas las URL.
> El buzón de contacto es `aminansoporte@gmail.com` (6-sep-2026), el mismo de las
> páginas legales y de la ficha de Play.

> ⚠️ **El `<title>` de `index.html` es el nombre del sitio en Google.** Cambiarlo cambia
> cómo nos llama el buscador en todos los resultados del dominio. No tocarlo a la ligera.

> ⚠️ **`/favicon.ico` en la raíz no se puede borrar.** Es el que mira Google, aparte del
> `<link rel="icon">`. Google solo admite **un favicon por dominio** (lo lee de esta
> portada, no de `/caostotal-neon/`), así que **aquí va el icono del JUEGO**, pedido
> por Faussi el 6-sep-2026: `favicon.ico` y `img/juego-icon-*.png`. Los
> `img/icon-*.png` con la A de Aminan siguen para el logo de la marca (`og:image`,
> `Organization.logo`). Si se cambia el icono, se cambia también en `caostotal-web`.

> La `<meta name="google-site-verification">` es la misma etiqueta que lleva la web del
> juego (el token es de la cuenta de Google, no de la propiedad). Permite dar de alta
> la raíz del dominio en Search Console con el método «etiqueta HTML».

## Qué hay

| Fichero | Para qué |
|---|---|
| `index.html` | La portada: marca, tarjeta enlazando a la web de Caos Total Neon y, debajo, enlace a su ficha de Google Play (publicado el 10-sep-2026) |
| `favicon.ico` | En la raíz a propósito, para Google |
| `img/` | El logotipo en varios tamaños y el banner del juego |
| `robots.txt`, `sitemap.xml` | Indexación de todo el dominio |

Sin scripts, sin fuentes externas, sin CDN.

## Los otros dos sitios del dominio

- `/caostotal-neon/` → repo `caostotal-neon`, la web del juego.
- `/caostotal-legal/` → repo `caostotal-legal`, los documentos legales.

Cada uno se despliega desde su propio repo. Este solo manda en la raíz.
