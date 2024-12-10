---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: colorful-header.jpg
widget1:
  title: "Collections Modules"
  url: 'http://kam535.github.io/sturdy-broccoli/collections/'
  image: colorful-header.jpg
  text: 'All of the lessons for the Collections group of fellows'
widget2:
  title: "Collections Modules"
  url: 'http://kam535.github.io/sturdy-broccoli/text/'
  image: colorful-header.jpg
  text: 'All of the lessons for the Text group of fellows'
widet 3:
  title: "All Modules"
  url: 'http://kam535.github.io/sturdy-broccoli/modules/'
  image: colorful-header.jpg
  text: 'All of the lessons for all fellows'
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
