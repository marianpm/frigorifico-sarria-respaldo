# Frigorífico Sarria — respaldo del sitio

Este repositorio contiene los archivos del sitio como archivos Git normales: `index.html`, `assets/`, `forms/`, `robots.txt` y `sitemap.xml`, entre otros. La copia del 5 de octubre de 2026 contiene 144 archivos. También se conserva `frigorifico-sarria-2026-10-05.zip` como respaldo adicional de la misma versión.

## Cómo recuperarlo

Desde el botón **Code** de GitHub podés descargar el repositorio completo como ZIP o clonarlo con Git. `index.html` debe quedar en la raíz. Para publicar la página, subí el contenido al servidor de `frigorificosarria.com`; los formularios necesitan PHP y correo configurado allí. Los cambios en este repositorio no actualizan automáticamente el dominio público.

Este repositorio conserva una copia de los archivos, pero no el historial de commits del repositorio anterior. El flujo manual `.github/workflows/importar-respaldo.yml` se usó para extraer el ZIP; no conviene volver a ejecutarlo después de modificar archivos, porque podría restaurar la versión archivada.

## Cambios incluidos

Metadatos SEO y para compartir, idioma `es-AR`, URL canónica, datos estructurados, mapa del sitio, imágenes de portada más livianas y carga diferida de imágenes fuera de la portada. También se corrigió el enlace al catálogo PDF y se retiraron las presentaciones «Jamón crudo español» y «Jamón crudo medio», que no tenían fotos.
