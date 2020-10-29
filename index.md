---
layout: default
---

We are committed to putting our community first and have created a whole new Developer Relations Team to take care of building a user-led ecosystem for developers who want to innovate on bare metal - and with interconnection - with the world’s digital infrastructure company.

## We Are In Service To You

We follow a simple [code of conduct](./CODE_OF_CONDUCT.html). TL;DR be kind.

<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
