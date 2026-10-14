# Pendientes del repositorio plantilla

Estado al 14 de octubre de 2026. Contenido preparado por IS · Instructional Designer, solo en local. Nada se ha creado ni publicado en GitHub.

## Bloqueante

1. **Publicación en GitHub: sin OK.** No se crea, sube ni publica este repositorio en GitHub hasta que IS · Educational Content Lead confirme el OK de Sho.

## Decisiones de Sho

2. **Repositorio público de Sho para el bloque 1: sin OK.** Debe ser público, sin datos de clientes, y tener historial, una rama, un PR de diseño y URL publicada. El ejercicio 1 no lo enlaza hasta que se decida.
3. **Ensayo del lunes 19 de octubre: sin OK.** Propuesto de unos 45 minutos, hora por definir. Ahí se valida la estimación de 15 minutos del trabajo previo y el tiempo de la primera publicación en Pages.
4. **Dueño del repositorio plantilla y cuenta u organización donde vive:** sin decidir. El tablero de propuestas depende de esto.

## Estructura de Pages (confirmada por IS · Full-stack Engineer, 14 oct)

- Se publica con **Deploy from a branch**, desde `main` y en la raíz. No se usa `/docs` ni GitHub Actions.
- No hay dominio propio y todas las rutas son relativas, porque el sitio vive bajo `/nombre-del-repo/`. Revisado: no hay rutas que empiecen con `/`.
- No hay paso de compilación y se mantiene `.nojekyll`.
- Activar Pages sigue siendo un paso manual de la preparación previa (paso 3 del README): Settings > Pages > main / root > Save, con la URL esperada. **Falta la captura** de ese paso, que se toma cuando exista el repositorio en GitHub.
- Tablero de propuestas: un issue fijado, sin plantilla de issue. La plantilla de pull request está en `.github/pull_request_template.md`.
- **Prueba (IS · Full-stack Engineer, viernes 16 de octubre):** activa **Template repository**, crea una copia con **Use this template**, activa Pages y verifica que la copia se publique y que las rutas funcionen. **Abierto:** la prueba necesita una cuenta distinta a la de Sho. Si no hay una, se prueba en la misma cuenta y queda anotado.

## Producción relacionada (fuera de este repositorio)

- Enlaces del formulario de evidencias y del tablero: se agregan al README cuando existan (Growth).
- Capturas verticales de la guía, cápsula de 3 minutos y video del paso de Pages (Content & Brand).
- Revisión de textos por IS · Educational Content Lead.
