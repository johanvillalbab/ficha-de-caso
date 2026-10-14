# Mi ficha de caso: plantilla del workshop "GitHub para diseñadores"

Este repositorio es la plantilla del workshop gratuito "GitHub para diseñadores" de Interface School (miércoles 21 de octubre de 2026, 5:00 a 6:30 p. m., hora de Colombia). Un repositorio es la carpeta de un proyecto que guarda sus archivos junto con el historial de cada cambio.

Contiene una página web sencilla con una ficha de caso de diseño, lista para publicarse con GitHub Pages, el servicio de GitHub que convierte un repositorio en una página con URL pública. Durante el workshop vas a cambiar esa ficha, proponer el cambio y revisarlo con otra persona, igual que harías con un diseño en Figma.

Todo se hace desde el navegador, en computador o celular. No necesitas instalar nada ni usar la terminal.

> Este repositorio es público. No subas datos de clientes ni información confidencial.

## Conceptos que vas a usar

- **Repositorio:** la carpeta del proyecto, con su historial completo.
- **Commit:** un cambio guardado, con un mensaje que explica qué cambió y por qué. Piensa en una versión con nombre en el historial de Figma.
- **Rama:** una copia paralela del proyecto donde pruebas un cambio sin tocar la versión principal (`main`). Se parece a duplicar una página de Figma para explorar.
- **Pull request (PR):** la propuesta de llevar los cambios de tu rama a `main`. Otra persona la revisa y comenta antes de integrarla.
- **Merge:** integrar el PR aprobado en `main`.

## Trabajo previo (antes del 21 de octubre)

Te toma unos 15 minutos. Es una estimación que se valida en el ensayo técnico. Si no alcanzas a hacerlo, el bloque 2 del vivo te ayuda a ponerte al día.

### Paso 1. Crea tu cuenta de GitHub

Regístrate en [github.com/signup](https://github.com/signup) y verifica tu correo.

Resultado esperado: entras a GitHub y ves tu nombre de usuario arriba a la derecha.

### Paso 2. Crea tu repositorio desde esta plantilla

1. En esta página, selecciona el botón verde **Use this template** y luego **Create a new repository**.
2. En **Repository name**, escribe un nombre corto en minúsculas, por ejemplo `ficha-de-caso`.
3. Deja la opción **Public** marcada. GitHub Pages gratuito solo publica repositorios públicos.
4. Selecciona **Create repository**.

Resultado esperado: estás en `github.com/tu-usuario/ficha-de-caso` y ves los mismos archivos de esta plantilla.

### Paso 3. Activa GitHub Pages

1. En tu repositorio, entra a **Settings** (en celular puede estar dentro del menú **···**).
2. En el menú lateral, selecciona **Pages**.
3. En **Build and deployment**, en **Source**, elige **Deploy from a branch**.
4. En **Branch**, elige `main` y la carpeta `/ (root)`. Selecciona **Save**.

Resultado esperado: después de uno o dos minutos, al recargar la página aparece el aviso **Your site is live at** con tu URL.

### Paso 4. Copia tu URL pública y envíala

Tu URL tiene esta forma: `https://tu-usuario.github.io/ficha-de-caso/`. Ábrela y pégala en el formulario de evidencias del workshop (el enlace llega por correo).

Resultado esperado: la URL muestra la ficha de caso con el título "Rediseño del flujo de pago".

Si la URL muestra un error 404, espera dos minutos y recarga. Si sigue igual, revisa que en el paso 3 elegiste `main` y `/ (root)`.

### Opcional

Mira la cápsula de 3 minutos sobre repositorio, commit, rama y PR. El vivo no depende de ella.

## Cómo se produce la evidencia de cada resultado

Cada resultado del workshop deja un enlace que puedes compartir. Así sabes que lo lograste, aunque veas la grabación.

| Resultado | Qué haces | Enlace de evidencia | Cuándo |
| --- | --- | --- | --- |
| 1. Publicar tu repositorio con GitHub Pages | Pasos 2 a 4 del trabajo previo | Tu URL `https://tu-usuario.github.io/ficha-de-caso/` en el formulario | Trabajo previo o bloque 2 |
| 2. Proponer un cambio en una rama con un commit que dice qué cambió y por qué | [Ejercicio 3](ejercicios/03-rama-y-commit.md) | Historial de tu rama: `github.com/tu-usuario/ficha-de-caso/commits/nombre-de-tu-rama` | Bloque 3 |
| 3. Abrir un PR que explica el cambio como decisión de diseño | [Ejercicio 4](ejercicios/04-abrir-pull-request.md) | Enlace del PR: `github.com/tu-usuario/ficha-de-caso/pull/1` en el formulario | Bloque 4 |
| 4. Revisar el PR de otra persona con un comentario concreto | [Ejercicio 5](ejercicios/05-revisar-pr-ajeno.md) | Enlace a tu comentario en el PR ajeno (menú **···** del comentario, **Copy link**) | Bloque 5 o después, en asíncrono |
| 5. Integrar tu PR y ver el cambio en tu URL | [Ejercicio 6](ejercicios/06-integrar-y-ver.md) | Tu misma URL de Pages, que ahora muestra la versión nueva | Bloque 6 o después, en asíncrono |

## Qué hay en este repositorio

- `index.html`: la ficha de caso que vas a editar.
- `estilos.css`: los estilos de la página. Puedes cambiar colores y tipografía en las primeras líneas.
- `img/`: imágenes de la ficha. Puedes reemplazarlas por las tuyas.
- `.github/pull_request_template.md`: la descripción que aparece sola cuando abres un PR.
- `ejercicios/`: un archivo por bloque del workshop, con variante para quien ve la grabación.
- `guia-seguimiento.md`: qué hacer después del workshop, incluido tu primer cambio en el repositorio de tu equipo.

## Si ves la grabación

La grabación tiene un capítulo por bloque. Cada ejercicio incluye una variante asíncrona para hacerlo a tu ritmo, y los enlaces de evidencia funcionan igual después del 21 de octubre.
