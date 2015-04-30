---
layout: page
title: Miscellaneous
tagline: Stuff I couldn't find a better place for
group: navigation
---
{% include JB/setup %}

## Vanity Links

* [My Google Scholar Page](https://scholar.google.com/citations?hl=en&user=F_zYX30AAAAJ)

## Other links

* [Web-based equation tool](http://www.sciweavers.org/free-online-latex-equation-editor)
* [Web-based FSM tool](http://madebyevan.com/fsm/)
* [Web-based diff tool](diff.html)
* [Procedural Jigsaw Puzzles](http://n-e-r-v-o-u-s.com/projects/puzzles/)
* [site pages](pages.html)
* VLC stuff
  * [VLC command lines](https://www.videolan.org/doc/streaming-howto/en/ch04.html)
  * [VLC GUI stuff](http://www.videolan.org/doc/streaming-howto/en/ch02.html)
  * [webcam testing](https://help.ubuntu.com/community/Webcam)

## Recent [Blog](/blog/) Posts

<ul class="posts">
  {% for post in site.posts limit:8 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
