---
layout: page
title: Grab your bow, mount your steed, and set out on an adventure!
screenshots:
    - "Arrowpoint 01"
    - "Arrowpoint 02"
    - "Arrowpoint 03"
    - "Arrowpoint 04"
    - "Arrowpoint 05"
---

<div class="windows-surface">
    <div class="video">
        <iframe src="//www.youtube.com/embed/{{ site.theme_settings.youtube_id }}" frameborder="0" allowfullscreen></iframe>
    </div>
</div>
<br />

<div id="steam_widget">
    <iframe src="//store.steampowered.com/widget/{{ site.theme_settings.steam_id }}" frameborder="0" width="900" height="190"></iframe>
</div>

### About the Game
Take aim and make your name as an epic monster hunter. Rumors tell of a terrible beast which roams the desert. Grab your bow, mount your steed, and set out on an adventure! This is a short, focused game about hitting targets with arrows and slaying a giant monster.

### Screenshots
<ol class="screenshots">
{% for screenshot in page.screenshots %}
    <li><a href="screenshots/{{ screenshot }}.jpg"><img src="screenshots/{{ screenshot }} Thumbnail.jpg" /></a></li>
{% endfor %}
</ol>