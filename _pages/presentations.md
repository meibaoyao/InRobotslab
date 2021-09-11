---
title:"Presentations"	
layout:gridlay
excerpt:"Presentations"
sitemap:false
permalink:/presentations/
---
Talks
{% for talk in site.data.presentationlist %}
{% if talk.invited == 1 %} {{ talk.title }}, presented by {{ talk.presenter }} at {{ talk.meeting }}, {{ talk.date }}, {{ talk.location }}. (Invited) {% endif %}
{% if talk.invited == 0 %} {{ talk.title }}, presented by {{ talk.presenter }} at {{ talk.meeting }}, {{ talk.date }}, {{ talk.location }}. {% endif %}
{% endfor %}
Posters
{% for poster in site.data.presentationlist %}
{{ poster.title }}, presented by {{ poster.presenter }} at {{ poster.meeting }}, {{ poster.date }}, {{ poster.location }}.
{% endfor %}
