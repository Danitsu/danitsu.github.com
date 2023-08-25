---
title: Crea tu primer website en Github
author: Dani
date: 2023-08-25 10:00:00 +0800
categories: [Guia]
tags: [blog, github]
pin: true
math: true
mermaid: true
#image:
 # path: /assets/img/favicons/danitsu.png
  #lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
  #alt: Dani ❤
---

> Te dejo un paso a paso de como poder crear tu primera pagina web en Github.

### Sigue los siguientes pasos

1. Crea una cuenta en Github (github.com).
2. Busca en google tu tema favorito, te dejo unos ejemplos (https://github.com/topics/blog-template).
3. Cuando tengas elegido tu tema favorito debes de realizar un "fork" en el repositorio, con esto igualmente apoyas al creador del contenido.

![Desktop View](/assets/img/favicons/other/fork.png){: .normal }

4. Una vez hecho el fork haz click en "settings" en el mismo repositorio.

![Desktop View](/assets/img/favicons/other/setting.png){: .normal }

5. Edita la URL de tu website, recuerda que el nombre debe seguir la siguiente estructura: USUARIOGITHUB.github.io

![Desktop View](/assets/img/favicons/other/newname.png){: .normal }

6. Si no pagas un plan en Github, debe encontrarse publico el repositorio.

### Ejemplo > Utilizando template Jekyll

1. Crea una cuenta en Github (github.com).

2. Realiza un "fork" en el repositorio [**Jekyll Theme Chirpy**](https://github.com/cotes2020/jekyll-theme-chirpy).

7. Para poder utilizar este template debes de instalar [**Jekyll**](https://jekyllrb.com/docs/installation/) y [**Node.js**](https://nodejs.org/es).

8. Clona tu repositorio en tu maquina, puedes utilizar [**Github Desktop**](https://desktop.github.com) para esto. 

9. En la raiz de tu repositorio ejecuta:
```
bash tools/init
bundle
```

10. Una vez realizado lo anterior podras customizar a tu gusto el template. Puedes modificar las variables (url, avatar, timezone, lang) que se encuentran configuradas en _config.yml.

11. Para visualizar localmente este antes de que realices la publicacion puedes utilizar el siguiente comando:
```
bundle exec jekyll s
```

12. Puedes realizar la implementación mediante acciones de GitHub, para ello debes de realizar lo siguiente:
```
Selecciona "settings > Pages" luego de esto baja hasta donde dice "Build and deployment > source" selecciona "Github Actions"
```

13. Una vez que tengas listo los pasos anteriores podras hacer un commit y push a github lo que gatillara el flujo de trabajo. En la pestaña acciones del repositorio podras ver como se va ejecutando, una vez que la compilacion haya finalizado con exito el sitio se implementara automaticamente. 

`Y listo!` con esto ya puedes empezar a crear tu primer blog en github. 