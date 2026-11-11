# SITRA-CGE UNL: documentación

Sitio publicado: <https://brtrl3.github.io/sitra-cge-docs/>

Este repositorio solo publica la documentación del proyecto
[RCL05/seguimiento_de_recomendaciones_CGE](https://github.com/RCL05/seguimiento_de_recomendaciones_CGE).
Las fuentes se editan allí, en `docs/` y `DOCUMENTACION/`; aquí no se edita contenido.

## Cómo se actualiza

El flujo `Publicar documentación` descarga la rama `main` del repositorio del proyecto,
compila el sitio con Quarto y lo publica en GitHub Pages. Se ejecuta:

- todos los días a las 06:00 (hora de Ecuador);
- a mano, desde la pestaña **Actions** o con:

  ```bash
  gh workflow run publicar.yml -R BrTrl3/sitra-cge-docs
  ```
