## Cookbook

A random selection of tutorials for how to accomplish certain tasks.

## Self-Hosted Installations

{% for menu-item in site.data.menus.sidebar %}
<ul>
  <li><a href="{{menu-item.url}}">{{ menu-item.title }}</a></li>
</ul>
{% endfor %}
