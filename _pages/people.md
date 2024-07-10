---
title: "ICT-PAG - Team"
layout: gridlay
excerpt: "ICT-PAG: Team members"
sitemap: false
permalink: /team/
---

## Group Members

### Academic Staff

<!-- Jump to [PhD students](#phd), [Master students](#masters) -->

{% assign number_printed = 0 %}
{% for member in site.data.faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<h4><a href="{{member.homepage}}">{{ member.name }}</a></h4> <br />
<i>{{ member.info }}</i>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

### PhD Students


### Master Students