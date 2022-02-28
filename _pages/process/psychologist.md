---
layout: archive
title: "Сторінка психолога"
permalink: /process/psychologist/
sidebar:
  nav: "sidebar-menu"
---
Група фахових психологів готова надавати психологічну допомогу дорослим і дітям - у разі необхідності.

<iframe src="https://drive.google.com/file/d/1z0CtmNAUmXURjs3c8TIomDJEPLqv6hIG/preview" width="640" height="480" allow="autoplay"></iframe>

Інформація для тих родин, що потребують педіатричної допомоги
<iframe src="https://drive.google.com/file/d/1NZY6pNmK8ffX_ciyKx4UaJOr5j2NOYpC/preview" width="640" height="480" allow="autoplay"></iframe>

5 кроків допомоги - психологічні дії, направлені на те, щоб заспокоїти людину 
<iframe src="https://drive.google.com/file/d/1yeNbEGd-mMlptiH9nW5VmwkibT6_keHv/preview" width="640" height="480" allow="autoplay"></iframe>

Психологічна допомога дитині під час надзвичайної ситуації 
<iframe src="https://drive.google.com/file/d/1nCRc8XRdrOd3-58g6xFo9metkxPGrAcd/preview" width="640" height="480" allow="autoplay"></iframe>

Набір ігор - для спокійного спілкування з усією родиною
<iframe src="https://drive.google.com/file/d/11pSx-gaZWmWLvMDBaUmS_4663hOFsX6r/preview" width="640" height="480" allow="autoplay"></iframe>


<div class="grid__wrapper">
  {% for post in site.posts %}
    {% if post.categories contains "Сторінка психолога" %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
