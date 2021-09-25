<h2>{{ site.data.site_list.docs_list_title }}</h2>
<ul>
   {% for item in site.data.site_list.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
