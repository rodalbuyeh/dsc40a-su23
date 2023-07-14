---
layout: home
title: Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}


 {: .important } 
Midterm is on Wednesday (7/19) during lecture. See pinned post in Campuswire for details on format. 

Click the 📺 icons below to view lecture recording, and ✏️ for annotated notes. 



<!-- [Jump to the current week](#week-03){: .btn } -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
