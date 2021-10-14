---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---

{% include parallax_image.html collection='tmsdocmock' pid='wright023' y='50%' %}

Browse the digital collection

{% include facet_gallery.html
collection='tmsdocmock' facet_by='type' num_column=4 %}

Browse the oral histories -- to be added soon

{% include facet_gallery.html
collection='tmsoh' facet_by='type' num_column=4 %}
