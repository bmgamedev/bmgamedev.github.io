---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

---

<ul class="nav navbar-nav">
  {% comment %}Jekyll can now sort on custom page key{% endcomment %}
  {% assign pages = site.pages | sort: 'weight' %} 
  {% for p in pages %}
    {% if p.menu == "main" %}
      <li{% if p.url == page.url %} class="active"{% endif %}>
         <a href="{{ site.baseurl }}{{ p.url }}">{{ p.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

AAHHHHH
