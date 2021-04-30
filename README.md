<h2>Contributors</h2>

{% for s in site.stu %}
  <img src="{{ s.image }}">
  <h2>{{ s.name }} - {{ s.user }}</h2>
  <h2>{{ s.content | markdownify }}</h2>
{% endfor %}
 
