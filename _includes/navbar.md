{% for item in site.navigation_bar_documents %}
    <a href="{{site.url}}/{{ item.url }}" class="btn">{{ item.title }}</a>
{% endfor %}