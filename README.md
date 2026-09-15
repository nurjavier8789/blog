# Welcome to my personal blog!
 Most of my blog is in Indonesian. You can always translate it to English.

## Latest Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%d %B %Y" }}
    </li>
  {% endfor %}
</ul>
