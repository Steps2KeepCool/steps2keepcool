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

<table>
  <tr>
    <th scope="col">Title</th>
    <th scope="col">Link</th>
    <th scope="col">Description</th>
    <th scope="col">Tweet</th>
  </tr>
{% for item in site.data.storage %}
  <tr>
    <td>{{ item.title }}</td>
    <td>{{ item.articleLink }}</td>
    <td>{{ item.desc }}</td>
    <td>{{ item.tweetLink }}</td>
  </tr>
{% endfor %}
</table>

{{content}}
