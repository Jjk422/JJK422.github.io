<h2>{{ site.data.simpleNavList.docs_list_title }}</h2>
<ul class="navbar_style">
   {% for item in site.data.simpleNavList.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>