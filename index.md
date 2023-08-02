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


 {: .note } 
Final will be closed books/notes/electronics/web. You will be allowed to keep with you two A4-sized sheets (four sides) with any content you want.

 {: .challenge } 
If 85% or greater response rate on SET evaluations (formerly CAPE) by August 4, class gets a 0.5% collective boost to overall grade. 

Click the 📺 icons below to view lecture recording, and ✏️ for annotated notes. 



<!-- [Jump to the current week](#week-03){: .btn } -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
