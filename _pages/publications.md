

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <u><a href="https://scholar.google.com/citations?user=xQFdaysAAAAJ">my Google Scholar profile</a></u>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}





