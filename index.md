---
---

# {{ site.title }}, {{ site.time | date_to_string }}

{% include radar.html %}

## What is the Tech Radar?

The dxw Tech Radar is a list of technologies, complemented by an assessment result, called _ring assignment_. We use four rings with the following semantics:

{% for ring in site.data.rings %}
* **{{ ring.name }}** - {{ ring.description }}
{% endfor %}

## What is the purpose?

The Tech Radar is a tool to inspire and support engineering teams at dxw to pick the best technologies for new projects; it provides a platform to share knowledge and experience in technologies, to reflect on technology decisions and continuously evolve our technology landscape. It's based on the [pioneering work of ThoughtWorks](https://www.thoughtworks.com/radar), and uses the open source visualisation created by [Zalando](https://github.com/zalando/tech-radar). Our Tech Radar sets out the changes in technologies that are interesting in software development &mdash; changes that we think our engineering teams should pay attention to and consider using in their projects.

## How do we maintain it?

The Tech Radar is maintained by the dxw Tech Team. The Tech Radar depends on active participation and input from all engineering teams at dxw.
