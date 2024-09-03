

{% if site.author.googlescholar %}

You can find my articles on my Google Scholar profile. {% endif %}
{% include base_path %}

{% for post in site.publications reversed %} {% include archive-single.html %} {% endfor %}
