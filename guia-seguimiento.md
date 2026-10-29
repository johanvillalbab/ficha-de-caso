# Guía de seguimiento: después del workshop

Workshop "GitHub para diseñadores": jueves 5 de noviembre de 2026, de 4:00 a 5:00 p. m., hora de Colombia. Repositorio plantilla: [este repositorio](README.md).

En el vivo creaste tu repositorio desde la plantilla, hiciste un commit en una rama y abriste un pull request (PR, la propuesta de cambio que otra persona revisa antes de integrarla). Esta guía cubre lo que no se practicó en la sesión de 1 hora y te ayuda a repetir el flujo en tu trabajo.

## 1. Termina lo que te faltó

Si no alcanzaste a abrir tu PR en el vivo, repite los [ejercicios 3 y 4](ejercicios/) y pega el enlace del PR en el [formulario de evidencias](https://www.interfaceschool.co/cursos/workshop-github/evidencia). El [tablero de propuestas](https://github.com/johanvillalbab/ficha-de-caso/issues/1) y esta plantilla siguen abiertos después del jueves 5 de noviembre.

## 2. Recorrido por un repositorio real

Antes de seguir, mira cómo se ve el flujo en un proyecto de verdad. Abre un repositorio público de un proyecto de diseño que conozcas y ubica cuatro cosas: el historial de commits, una rama, un PR de diseño con su conversación y la URL publicada.

## Si tu repositorio quedó privado

Para compartir tu PR en el tablero y en el formulario, tu repositorio tiene que ser público (Public).

1. En tu repositorio, entra a **Settings** (en celular puede estar dentro del menú **···**).
2. Baja hasta el final, a **Danger zone**.
3. Selecciona **Change visibility** y elige **Public**. GitHub te pide confirmar.

Recuerda: en un repositorio público no subas datos de clientes ni información confidencial.

## 3. Publica tu página con GitHub Pages

GitHub Pages es el servicio de GitHub que convierte un repositorio en una página con URL pública.

1. En tu repositorio, entra a **Settings** (en celular puede estar dentro del menú **···**).
2. En el menú lateral, selecciona **Pages**.
3. En **Build and deployment**, en **Source**, elige **Deploy from a branch**.
4. En **Branch**, elige `main` y la carpeta `/ (root)`. Selecciona **Save**.
5. Después de uno o dos minutos, recarga. Aparece **Your site is live at** con tu URL, de la forma `https://tu-usuario.github.io/ficha-de-caso/`.
6. Pega esa URL en el [formulario de evidencias](https://www.interfaceschool.co/cursos/workshop-github/evidencia).

Si ves un error 404, espera dos minutos y recarga. Si sigue igual, revisa que elegiste `main` y `/ (root)`.

## 4. Revisa el PR de otra persona

Sigue el [ejercicio 5](ejercicios/05-revisar-pr-ajeno.md). Abre el [tablero de propuestas](https://github.com/johanvillalbab/ficha-de-caso/issues/1), elige el PR anterior al tuyo y deja al menos un comentario concreto: qué funciona, qué cambiarías y por qué. Si puedes, apóyalo con una captura. Copia el enlace de tu comentario (menú **···** del comentario, **Copy link**) y pégalo en el formulario.

## 5. Responde, integra tu PR y mira el cambio

Sigue el [ejercicio 6](ejercicios/06-integrar-y-ver.md).

1. Responde el comentario que recibiste en tu PR. Si te pidieron un ajuste, haz un commit nuevo en la misma rama.
2. Selecciona **Merge pull request** y luego **Confirm merge**. Merge significa integrar el PR aprobado en `main`.
3. Abre tu URL de Pages y comprueba que muestra la versión nueva. Puede tardar uno o dos minutos.

## 6. El flujo completo, de punta a punta

En esta guía tienes la secuencia completa que en el vivo no alcanzamos a mostrar entera: repositorio desde la plantilla, rama, commit, PR, revisión, merge y página publicada. Repítela una vez más con otro cambio pequeño en tu ficha, sin mirar los pasos. Si la completas sola o solo, ya puedes llevarla a tu equipo.

## 7. Tu primer cambio el lunes

El objetivo es hacer un cambio pequeño en un repositorio de tu equipo, con el mismo flujo del workshop.

1. **Pide el repositorio correcto.** Pregunta a alguien de desarrollo cuál repositorio contiene la parte que diseñas (textos, íconos, estilos o documentación).
2. **Pide el acceso justo.** Para proponer cambios sin integrarlos necesitas permiso de escritura (rol **Write**) o, en repositorios abiertos, puedes trabajar desde una copia. Pide solo lo necesario y pregunta si el equipo tiene reglas para nombrar ramas.
3. **Elige un cambio de bajo riesgo.** Un texto de interfaz, un error ortográfico o una línea del README. Evita archivos que no entiendas.
4. **Crea una rama y haz un commit** con un mensaje que diga qué cambió y por qué.
5. **Abre el PR** con problema, cambio, por qué, antes y después, y qué revisar. Si el repositorio no tiene plantilla de PR, usa la de este repositorio.
6. **Pide revisión** a la persona dueña de esa parte del código y deja que ella haga el merge si así trabaja el equipo.

## 8. Revisa PR de tu equipo

Pide que te agreguen como revisora o revisor en los PR que cambian la interfaz. Un comentario con captura y criterio de diseño ahorra iteraciones.

## 9. Para seguir aprendiendo

Quedaron fuera del vivo y puedes explorarlos después: GitHub Desktop, publicar en Vercel y usar un dominio propio.

> Recuerda: tus repositorios de práctica son públicos. No subas datos de clientes.
