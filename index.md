---
layout: page
title: Score board
subtitle: Gain ROOT and Earn Points
use-site-title: true

---

<style>
img {
  width: 100%;
  height: auto;
}
</style>



<div class="photo-gallery">
  {% for image in page.images %}
  <li style="list-style-type:none">
    <center>
      <a href="{{image.link}}">
        <img src="{{ image.image_path }}" alt="{{ image.title }}">
      </a>
      {{image.title}}
    </center>
  </li>
  {% endfor %}
</div>

{% if paginator.total_pages > 1 %}
<ul class="pager main-pager">
  {% if paginator.previous_page %}
  <li class="previous">
    <a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&larr; Newer Posts</a>
  </li>
  {% endif %}
  {% if paginator.next_page %}
  <li class="next">
    <a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Older Posts &rarr;</a>
  </li>
  {% endif %}
</ul>
{% endif %}

<h2>Last Update at : 4-21-2019</h2>

| Players       | Score         | Rank     |
|:-------------:|:-------------:|:-----:|
|sc00by    |710           |01      |
|momo_tree       |    650        |02     |
|m0tley         |    600         |03       |
|Wesley           |   300       |04      |

|           |         |05       |
|       |              |06       |
|             |            |07       |
|                |               |08       |
|               |               |09       |
|               |               |10       |
|               |               |11       |
|               |               |12       |
|               |               |13       |
|               |               |14       |
|               |               |15      |
|               |               |16       |
|               |               |17       |
|               |               |18       |
|               |               |19       |
|               |               |20       |
|               |               |21       |


<h1>
  <a href="" class="typewrite" data-period="2000" data-type='[ "$nc -l -p 6996 -e cmd.exe"]'>
    <span class="wrap"></span>
  </a>
</h1>
