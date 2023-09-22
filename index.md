---
layout:  default
---

# My Projects
Here is a list of projects that I am working on:
# My Interests
I'm interested in learning about computers.
# My Blogd
<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url }}">{{ post.titles }}</a>
</li>
{% endfor %}
By there.
</ul>
# Get in Touch
<ul>
<li><a href="https://github.com/{{ site.github_username
  }}">GitHub</a></li>
</ul>