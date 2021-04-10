---
layout: default
---

<h2>Hello from {{ page.my_var }}</h2>

{% capture md %}
# Hello from markdown in the layout
## Sub-test
Test var substitution inside capture:
hello again from {{ page.my_var }}
{% endcapture %}
{{ md | markdownify }}

{% for item in site.data.storage %}
<p>Item title: {{ item.title }}</p>
{% endfor %}

{{content}}
