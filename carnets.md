---
layout: page
title: Carnets
---

Les études Anarchy et Instin possèdent leur propre carnet :

* [carnet de recherche Instin]({{ site.github.url }}/behindinstin/) avec Servanne Monjour
* [carnet de recherche Anarchy]({{ site.github.url }}/behindanarchy/) avec Ariane Mayer

De manière plus générale, quelques traces de mes recherches sont à trouver ici :
<div class="posts">
  <ul class="post">
  {% for post in site.categories.carnet %}
      <li>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    <span class="post-date">{{ post.date | date_to_string }}</span>
    </li>

    <!-- {{ post.content }} -->
  {% endfor %}
  </ul>
</div>

<div class="pagination">
  {% if paginator.next_page %}
    <a class="pagination-item older" href="{{ site.baseurl }}page{{paginator.next_page}}">Older</a>
  {% else %}
    <span class="pagination-item older">Older</span>
  {% endif %}
  {% if paginator.previous_page %}
    {% if paginator.page == 2 %}
      <a class="pagination-item newer" href="{{ site.baseurl }}">Newer</a>
    {% else %}
      <a class="pagination-item newer" href="{{ site.baseurl }}page{{paginator.previous_page}}">Newer</a>
    {% endif %}
  {% else %}
    <span class="pagination-item newer">Newer</span>
  {% endif %}
</div>
