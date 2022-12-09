---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
Testing the timeago plugin

{% assign date = '2022-05-15T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}
