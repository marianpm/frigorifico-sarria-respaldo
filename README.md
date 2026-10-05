# Frigorífico Sarria — respaldo privado

Este repositorio contiene los archivos del sitio como archivos Git normales: `index.html`, `assets/`, `forms/`, `robots.txt` y `sitemap.xml`, entre otros. La copia del 5 de octubre de 2026 contiene 144 archivos. También se conserva `frigorifico-sarria-2026-10-05.zip` como respaldo adicional de esa misma versión.

## Cómo recuperarlo

Desde el botón **Code** de GitHub podés descargar el repositorio completo como ZIP o clonarlo con Git. `index.html` debe quedar en la raíz. Para publicar la página, subí el contenido al servidor de `frigorificosarria.com`; los formularios necesitan PHP y correo configurado allí. Los cambios en este repositorio privado no actualizan automáticamente el dominio público.

Este repositorio conserva una copia de los archivos, pero no el historial de commits del repositorio anterior. El flujo manual `.github/workflows/importar-respaldo.yml` se usó una vez para extraer el ZIP; no conviene volver a ejecutarlo después de modificar archivos, porque podría restaurar la versión archivada.

## Cambios incluidos

Metadatos SEO y para compartir, idioma `es-AR`, URL canónica, datos estructurados, mapa del sitio, imágenes de portada más livianas y carga diferida de imágenes fuera de la portada. También se corrigió el enlace al catálogo PDF.

## Pendiente antes de publicar esta copia

`index.html` hace referencia a `assets/img/restaurant/jamon-crudo-español.avif` y `assets/img/restaurant/jamon-crudo-medio.avif`, pero esas dos fotos no estaban en la carpeta local. Hay que agregar las fotos correctas o retirar esas tarjetas antes de publicarla.
