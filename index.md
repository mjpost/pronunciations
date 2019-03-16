---
layout: default
title: ACL Name Pronunciations
---

Pronunciations.
Names are followed by a dictionary-style pronunciated for (American) English speakers.
Ideally, we also include [IPA](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet) or at least [Arpabet]((https://nlp.stanford.edu/courses/lsa352/arpabet.html)).

{% for entry in site.data.pronunciations %}
  {% if entry.website %}
- [{{ entry.name }}](entry.website)  ("{{ entry.gloss }}")
  {% else %}
- {{ entry.name }} ("{{ entry.gloss }}")
  {% endif %}

  {% if entry.arpabet %}
  - Arpabet: "{{ entry.arpabet }}"
  {% endif %}
  {% if entry.ipa %}
  - IPA: "{{ entry.ipa }}"
  {% endif %}
{% endfor %}

You can find the raw data [on Github](https://github.com/mjpost/pronunciations).
