# Créditos

## Autoría

{% for author in book.authors %}
* {{ author }}
{% endfor %}

<!--
### Colaboradores:

{% for collaborator in book.collaborators %}
* {{collaborator.name}} en {{collaborator.edited}}
{% endfor %}
-->
___

{% include "git+https://github.com/catedu/faq-aularagon.git/imagenes_creditos_intef.md" %}