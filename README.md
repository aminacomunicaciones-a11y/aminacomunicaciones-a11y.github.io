# aminacomunicaciones-a11y.github.io — portada del dominio

Portada de **Aminan Juegos**. Es el *sitio de usuario* de GitHub Pages: al llamarse el
repo exactamente igual que la cuenta, se publica en la **raíz** del dominio.

**En vivo:** https://aminacomunicaciones-a11y.github.io/

## Para qué existe

No es decorativo. Antes esta dirección devolvía el 404 de GitHub, y de ahí salían dos
cosas feas en los resultados de Google de **todo** el dominio:

| Problema | Causa | Lo arregla |
|---|---|---|
| El icono era el globo genérico | Google coge el favicon de la raíz del dominio | `/favicon.ico` con la A de Aminan |
| Ponía «GitHub Pages documentation» | Google coge el nombre del sitio del título de la portada | El `<title>` de aquí: **Aminan Juegos** |
| El `robots.txt` no se leía | `robots.txt` solo vale en la raíz | El `robots.txt` de aquí, que declara los dos sitemaps |

> ⚠️ **El nombre de la marca es «Aminan Juegos», con N.** Las grafías sin la N son
> incorrectas. Pero **el correo `amina.comunicaciones@gmail.com` y el dominio
> `aminacomunicaciones-a11y.github.io` sí llevan la grafía vieja y NO se tocan**: son
> direcciones reales y cambiarlas rompe el contacto y todas las URL.

> ⚠️ **El `<title>` de `index.html` es el nombre del sitio en Google.** Cambiarlo cambia
> cómo nos llama el buscador en todos los resultados del dominio. No tocarlo a la ligera.

> ⚠️ **`/favicon.ico` en la raíz no se puede borrar.** Es el que mira Google, aparte del
> `<link rel="icon">`.

## Qué hay

| Fichero | Para qué |
|---|---|
| `index.html` | La portada: marca, y tarjeta enlazando a la web de Caos Total: Neon |
| `favicon.ico` | En la raíz a propósito, para Google |
| `img/` | El logotipo en varios tamaños y el banner del juego |
| `robots.txt`, `sitemap.xml` | Indexación de todo el dominio |

Sin scripts, sin fuentes externas, sin CDN.

## Los otros dos sitios del dominio

- `/caostotal-neon/` → repo `caostotal-neon`, la web del juego.
- `/caostotal-legal/` → repo `caostotal-legal`, los documentos legales.

Cada uno se despliega desde su propio repo. Este solo manda en la raíz.
