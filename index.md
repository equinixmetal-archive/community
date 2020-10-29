---
layout: default
---

Equinix Metal™ is an automated, interconnected, low-latency bare metal-as-a-service, that is available in global locations across Platform Equinix®. We enable digital businesses to more quickly be at the center of the customers, suppliers, and partners with whom they want to connect.

We follow a simple [code of conduct](./CODE_OF_CONDUCT.html). TL;DR be kind.

<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
