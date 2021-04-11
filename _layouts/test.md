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
    <th scope="col">Summary</th>
    <th scope="col">Link</th>
    <th scope="col">More info</th>
    <th scope="col">Tweet</th>
  </tr>
{% for item in site.data.storage %}
  <tr>
    <td>{{ item.title }}</td>
    <td><a href="{{ item.articleLink }}">Link</href></td>
    <td>{{ item.desc }}</td>
    <td><a href="{{ item.tweetLink }}">Tweet</href></td>
  </tr>
{% endfor %}
</table>

<h2>Test enumerating subdirectory data files</h2>

{% for item_hash in site.data.techs.genericlists %}
  <p>Key: {{ item_hash[0] }} </p>
{% endfor %}


{{content}}
