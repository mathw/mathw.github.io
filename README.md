## Welcome!

I'm Matthew Walton. I'm a software developer, amateur musician, aikidoka, morris dancer, reader, cook, cat lover...

There'll be stuff here. Varied stuff.

### Posts

{% for post in site.posts %}
  {{ post.date | date_to_string }} [{{ post.title }}]({{ post.url }})
{% endfor %}
