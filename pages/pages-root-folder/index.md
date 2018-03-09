---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_roadmap_2.jpg
widget1:
  title: "Why Hyku?"
  url: '/why-hyku'
  image: widget-1-302x182.jpg
  text: 'Are you looking for an open-source platform for your digital library or institutional repository? <em>Hyku</em> offers a hyrax-in-a-box system to let you hit the ground running.'
widget2:
  title: "Our Parters"
  url: '/our-partners'
  image: widget-1-302x182.jpg
  text: 'Bridge2Hyku is a project by The University of Houston (UH) Libraries, in partnership and consultation with Indiana University at Bloomington (IUB) and Indiana University-Purdue University Indianapolis (IUPUI), The University of Victoria (UVic), and the University of Miami (UM).'
widget3:
  title: "Download Theme"
  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: '<em>Feeling Responsive</em> is free and licensed under a MIT License. Make it your own and start building. Grab the <a href="https://github.com/Phlow/feeling-responsive/tree/bare-bones-version">Bare-Bones-Version</a> for a fresh start or learn how to use it with the <a href="https://github.com/Phlow/feeling-responsive/tree/gh-pages">education-version</a> with sample posts and images. Then tell me via Twitter <a href="http://twitter.com/phlow">@phlow</a>.'
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
