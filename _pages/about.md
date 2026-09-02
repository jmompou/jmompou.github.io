---
permalink: /about/
title: "Academic Pages es una plantilla de GitHub Pages lista para usar en webs académicas personales"
author_profile: true
author: "Jorge Ibáñez Puertas (ES)"
lang: es
translation_url: /en/about/
redirect_from: 
  - /about.html
---

Esta es la página de presentación de un sitio web construido con la [plantilla Academic Pages](https://github.com/academicpages/academicpages.github.io) y alojado en GitHub Pages. [GitHub Pages](https://pages.github.com) es un servicio gratuito en el que las páginas web se generan y alojan a partir de código y datos guardados en un repositorio de GitHub, actualizándose automáticamente con cada nuevo commit. Esta plantilla es un fork del [tema Minimal Mistakes de Jekyll](https://mmistakes.github.io/minimal-mistakes/) creado por Michael Rose, ampliado para dar soporte al tipo de contenido propio del ámbito académico: publicaciones, un portfolio, entradas de blog y un CV generado dinámicamente. Estas mismas características la convierten también en una gran plantilla para cualquiera que necesite mostrar un perfil profesional.

Puedes hacer un fork de [esta plantilla](https://github.com/academicpages/academicpages.github.io) ahora mismo, modificar los ficheros de configuración y Markdown, añadir tus propios PDFs y demás contenido, y tener tu propia web gratis, sin anuncios.

Una web personal basada en datos
======
Como muchas otras plantillas de GitHub Pages basadas en Jekyll, Academic Pages separa el contenido de la web de su forma. El contenido y los metadatos de tu web están en ficheros Markdown estructurados, mientras que otros ficheros conforman el tema, especificando cómo transformar ese contenido y metadatos en páginas HTML. Estos ficheros Markdown (.md), YAML (.yml), HTML y CSS se guardan en un repositorio público de GitHub. Cada vez que haces commit y push de una actualización al repositorio, el servicio de [GitHub Pages](https://pages.github.com/) genera páginas HTML estáticas a partir de estos ficheros, alojadas gratuitamente en los servidores de GitHub.

Muchas de las funcionalidades de los sistemas de gestión de contenido dinámicos (como Wordpress) pueden conseguirse de esta forma, usando una fracción de los recursos computacionales y con mucha menos vulnerabilidad frente a ataques o DDoS. También puedes modificar el tema a tu gusto sin tocar el contenido de tu web. Si en algún momento rompes algo en Jekyll/HTML/CSS sin remedio, tus ficheros Markdown con tus publicaciones, etc. están a salvo. Puedes deshacer los cambios o incluso borrar el repositorio y empezar de nuevo — ¡solo asegúrate de guardar los ficheros Markdown!

Para quienes necesiten funcionalidad más avanzada, la plantilla también soporta estas herramientas populares:
- [MathJax](https://www.mathjax.org/) para ecuaciones matemáticas
- [Mermaid](https://mermaid.js.org/) para diagramas
- [Plotly](https://plotly.com/javascript/) para gráficos

Primeros pasos
======
1. Regístrate en GitHub si no tienes cuenta y confirma tu correo electrónico (obligatorio).
1. Haz un fork de [esta plantilla](https://github.com/academicpages/academicpages.github.io) pulsando el botón "Use this template" arriba a la derecha.
1. Ve a la configuración del repositorio (última pestaña de las que empiezan por "Code", debajo de "Unwatch"). Renombra el repositorio a "[tu-usuario-de-GitHub].github.io", que será también la URL de tu web.
1. Configura los ajustes generales del sitio y crea el contenido y los metadatos (ver más abajo).
1. Sube cualquier fichero (PDFs, .zip, etc.) al directorio files/. Aparecerán en https://[tu-usuario-de-GitHub].github.io/files/ejemplo.pdf.
1. Comprueba el estado yendo a la configuración del repositorio, en la sección "GitHub Pages".

Configuración general del sitio
------
El fichero de configuración principal del sitio está en el directorio base, en [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), que define el contenido de las barras laterales y otras funcionalidades globales. Tendrás que sustituir las variables por defecto por las tuyas propias y las de tu repositorio de GitHub. El fichero de configuración del menú superior está en [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). Por ejemplo, si no tienes portfolio o entradas de blog, puedes quitar esos elementos de ese fichero para que no aparezcan en la cabecera.

Crear contenido y metadatos
------
Para el contenido del sitio hay un fichero Markdown por cada tipo de contenido, guardados en directorios como _publications o _pages. Al principio de cada fichero Markdown hay datos estructurados en YAML que el tema utiliza para generar automáticamente listados, páginas individuales y demás.

**Generador de Markdown**

El repositorio incluye [un conjunto de Jupyter Notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) que convierten un CSV con datos estructurados de publicaciones o presentaciones en ficheros Markdown individuales con el formato correcto para la plantilla Academic Pages.

Cómo editar el repositorio de GitHub de tu web
------
Mucha gente usa un cliente git para crear ficheros en su ordenador y luego subirlos a los servidores de GitHub. Si no estás familiarizado con git, puedes editar directamente estos ficheros de configuración y Markdown desde la interfaz de github.com. Ve a un fichero y pulsa el icono del lápiz arriba a la derecha de la vista previa del contenido (a la derecha de los botones "Raw | Blame | History"). Puedes borrar un fichero pulsando el icono de la papelera junto al del lápiz. También puedes crear ficheros nuevos o subir ficheros navegando a un directorio y pulsando los botones "Create new file" o "Upload files".

Más información
------
Puedes encontrar más información sobre cómo configurar Academic Pages en [la guía](https://academicpages.github.io/markdown/), la [wiki en crecimiento](https://github.com/academicpages/academicpages.github.io/wiki), y siempre puedes [hacer una pregunta en GitHub](https://github.com/academicpages/academicpages.github.io/discussions). Las [guías del tema Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (del que se hizo fork) también pueden ser útiles.
