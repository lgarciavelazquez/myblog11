---
layout: post
title: "Este es mi primer post"
date: 2025-10-11
categories: jekyll posts tutorial
---

Este es el comienzo del post. Este post se encuentra en el directorio `_posts`. 

Vamos a mostrar algunas variables:


URL del sitio:
{{site.url}}

BASEURL del sitio:
{{site.baseurl}}

Titulo de la pagina:
{{page.title}}

URL de la pagina:
{{page.url}}

Categorias de la pagina:
{{page.categories}}


Vamos a mostrar algunas manera de insertar imagenes:

![whatsup]({{ site.url }}{{ site.baseurl }}/assets/img/whatsup.JPG){: .align-center }  

![redes]({{ site.url }}{{ site.baseurl }}/assets/img/redes.JPG){: .align-center }  

![eoi]({{ site.url }}{{ site.baseurl }}/assets/img/eoi.JPG){: .align-center }   

![whatsup]({{"/assets/img/whatsup.JPG"  | relative_url}})

![redes]({{"/assets/img/redes.JPG" | absolute_url}})  

![eoi]({{ site.baseurl }}/assets/img/eoi.JPG)   







