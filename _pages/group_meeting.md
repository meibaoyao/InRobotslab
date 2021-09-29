---
title: "Group meeting and journal club"
layout: textlay
excerpt: "Group metting"
sitemap: false
permalink: /group_meeting/
---

## Group Meeting and Journal Club Schedule

Group meettings are held every other week and journal club is held every week.

The normal time/place for Group meetings is Tues. 9:30-11:00 in 403 rom.

The normal time/place for Journal Club is Mon.9:30-11:30 in 709 rom

<b>Schedule is subject to change, please check frequently. </b>

{% for meeting in site.data.group_meeting %}

<b>{{ meeting.date}}</b>  {{ meeting.presenter}}
<br /> 

{% endfor %}


{% for journal in site.data.journal_club %}

<b>{{ journal.date}}</b>  {{ journal.presenter}}
<br /> 

{% endfor %}
