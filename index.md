---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<img style="float: right; border-radius: 50%; border-style: solid" src="/poperagnarok/foto_yo.jpg" class="foto_yo">

{% assign bib_file = '_bibliography/biblio.bib' %}
{% bibliography -f {{bib_file}} --style simple-ieee.csl --bibliography_list_tag ul %}
