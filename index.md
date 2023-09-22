---
layout:  default
---

# My Projects
Here is a list of projects that I am working on:
# My Interests
I'm interested in learning about computers.
# My Blog
<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>
# Get in Touch
<ul>
<li><a href="https://github.com/{{ site.github_username
  }}">GitHub</a></li>
</ul>