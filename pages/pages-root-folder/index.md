---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Pulp - 'Common people'"
  url: 'https://music-land.social/NaydiCanulDzidz.github.io/blog/'
  image: widget-1-302x182.jpg
  text: 'Durante mucho tiempo, fueron los grandes tapados del britpop. Jarvis Cocker y los suyos habían fundado el grupo en el Sheffield de 1978 y habían debutado en disco en 1983.'
widget2:
  title: "Musica de hoy en día"
  url: 'https://music-land.social/NaydiCanulDzidz.github.io/info/'
  text: 'Bangtan Sonyeondan, mejor conocido por sus siglas BTS, es un grupo surcoreano formado en Seúl en 2010 y que debutó en 2013 bajo la compañía Big Hit Music.​ Está compuesto por siete integrantes: Jin, Suga, J-Hope, RM, Jimin, V y Jungkook, quienes coescriben y coproducen la mayor parte de su material discográfico.'
  video: '<a href="https://www.youtube.com/watch?v=MBdVXkSdhwU" data-reveal-id="videoModal"><img src="https://music-land.social/NaydiCanulDzidz.github.io/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. The code is well-documented and explains you how it works.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
