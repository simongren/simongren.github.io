---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<h2>Journal articles:</h2>
		{% for post in site.publications reversed %}
		  {% include archive-single.html %}
		{% endfor %}


<h2>Work in progress:</h2>

		{% for post in site.currentwork reversed %}
		  {% include archive-single.html %}
		{% endfor %}

