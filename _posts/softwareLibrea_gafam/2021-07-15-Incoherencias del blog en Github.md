---
layout: post
title:  " Incoherencias del blog en Github" 
date:   2021-07-15
categories: es internet
tags: [es, blog, github, microsoft, gitea, codeberg, gitlab]
---

Hace unos meses decidí cambiar el blog de [Wordpress](https://izaroblog.com/2021/03/23/helbide-aldaketa-cambio-de-direccion/) dónde llevaba mucho tiempo escribiendo. Se me hacía cada vez más difícil entender los sistemas, opciones, y todas las complicaciones que iban añadiendo año tras año. 

Tenía ganas de escribir, sin preocuparme demasiado por cómo insertar fotos, cómo quedaría la cabecera, etc. Estuve preguntado por opciones de crear blogs simples, en los que se pudiese escribir en [Markdown](https://es.wikipedia.org/wiki/Markdown) tranquilamente, y me decanté por la posibilidad que daba [Githubpages](https://pages.github.com/). Prioricé otra vez la facilidad de instalarlo y hacerlo funcionar. Además puedo guardar en formato de texto simple todo el blog de forma cómoda y sin que pese mucho en mi ordenador. 
Metí bastantes horas intentando entender el funcionamiento de [Githubpages](https://pages.github.com/), comprendí lo mínimo de [Jekyll](https://jekyllrb.com/) para montar la web, y he ido poco a poco migrando mi blog, añadiendo cosas y sintiéndome más a gusto con la decisión.

> Pero claro... no todo el monte es orégano ni todo podía ser tan fácil! :D  

![Jekyll](https://jekyllrb.com/img/octojekyll.png)


[Github](https://es.wikipedia.org/wiki/GitHub) es propiedad de [Microsoft](https://es.wikipedia.org/wiki/Microsoft) y hace poco ha habilitado un "servicio" llamado [Copilot](https://copilot.github.com/), que resulta que [ignora bastentes licencias libres](https://sergiotarxz.me/2021/07/04/thoughts-about-github-copilot-license-laundry/). 
Si ya tenía cierta reticencia frente a que fuese el Señor Gates quien me alojara el blog, con esto notica me sentí un poco más incómodo. Realmente uso la plataforma únicamente para publicar mis escritos, porque de programación no tengo ni idea, pero bueno... 

Pregunté a la sabiduría ([Moribundo Insurgente](https://pleroma.libretux.com/@demoakracia),[Tarteka](https://pleroma.libretux.com/@tarteka),[Victorhck](https://mastodon.social/@victorhck) y [Marcel Costa](https://barcelona.social/users/marcelcosta)) del [Fediverso](https://es.wikipedia.org/wiki/Fediverso) y he recibido información de varias alternativas, con el "sistema Git":
- [Gitea](https://gitea.com/), parece ser que está más pensado para trabajar con programación, y no está pensado para hacer páginas.
- [Codeberg](https://victorhckinthefreeworld.com/2020/07/06/codeberg-alternativa-github-gitlab/) una alternativa muy interesante, pero que a día de hoy sólo permite crear en local la página. Además de que creo que funciona más con [html](https://es.wikipedia.org/wiki/HTML) y no soy un especialista en ese lenguaje! Eso si, el gran [Victorhck](https://mastodon.social/@victorhck) no ha perdido la ocasión de intentarlo y ha creado un [clon de mi blog](https://izaro.codeberg.page/) bastante interesante! ;)
- [GitLab](https://about.gitlab.com/), pese a que no esté en manos del señor Gates, su nube depende de [AWS(Amazon)](https://es.wikipedia.org/wiki/Amazon_Web_Services) y [GoogleCloud](https://es.wikipedia.org/wiki/Google_Cloud), con lo que sería saltar de la sartén al fuego.

![Codeberg](https://codeberg.org/img/logo.svg)

Tras haber estudiado, y revisado las opciones, por ahora me quedaré por [Githubpages](https://pages.github.com/) ya que no veo ninguna otra opción factible (con mis conocimientos). Esto que me supone añadir una incoherencia más a mi mochila.   
A veces resulta cansado buscar y rebuscar para encontrar la alternativa más acorde con tus principios, pero en la búsqueda siempre se aprende y se encuentran cosas interesantes para el futuro!

⚽️ Bolas extra: 
- [Eleventy](https://www.11ty.dev/) nos lo trae [Fedizen4](https://barcelona.social/titi) y [posibilita convertir los archivos md en html "mágicamente"](https://barcelona.social/notice/A9L7dygjPVqGURT3GC) ;), un ejemplo de instrucciones: <https://forja.laloka.org/laloka/laloka.org>
