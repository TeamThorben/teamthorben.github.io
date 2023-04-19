---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_drop.jpg
widget1:
  title: "Über uns"
  url: 'https://thorben.team/info/'
  image: header-bus.jpg
  text: 'Informationen zu unserem Team.'
widget2:
  title: "Baustelle"
  url: 'https://thorben.team/info/'
  text: 'Diese Seite befindet sich noch im <em>Aufbau</em>. Inhalte sind entsprechend unvollständig und noch nicht final.'
  video: '<a href="#" data-reveal-id="videoModal"><img src="./images/baustelle.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Blog"
  url: 'https://thorben.team/blog/'
  image: logo_kneipenquiz.png
  text: 'Blogeinträge mit Berichten zu den Kneipenquiz und weiteren Aktivitäten.'

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
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/7lWj2zR9ukc" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
