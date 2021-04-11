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

<h2>Test enumerating subdirectory data files</h2>

{% for item_hash in site.data.techs.genericlists %}
  <p>Key: {{ item_hash[0] }} </p>
  {% if item_hash[0] == page.my_var %}
    {% assign topiclist = item_hash[1] %}
    <p>  - topic list selected</p>
  {% endif %}
{% endfor %}

<table>
  <tr>
    <th scope="col">Summary</th>
    <th scope="col">Link</th>
    <th scope="col">More info</th>
    <th scope="col">Tweet</th>
  </tr>
{% for item in topiclist %}
  <tr>
    <td>{{ item.title }}</td>
    <td><a href="{{ item.articleLink }}">Link</href></td>
    <td>{{ item.desc }}</td>
    <td><a href="{{ item.tweetLink }}">Tweet</href></td>
  </tr>
{% endfor %}
</table>


{{content}}
