## Welcome
So. I was going to make an amazing custom theme for this website, but then I got bored and decided not too. This will do for now :).

-Picks

## Posts
{% for post in site.posts %}
   

### [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
By {{post.author}} in {{post.category}} on {{ page.date | date_to_long_string }}
{{ post.excerpt }}
[Read More]({{ site.baseurl }}{{ post.url }})
{% endfor %}
