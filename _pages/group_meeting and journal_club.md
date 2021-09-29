---
title: "Group meeting and journal club"
layout: textlay
excerpt: "Group metting"
sitemap: false
permalink: /group_meeting/
---

## Group Meeting Schedule

Group meettings are held every other week.   

The normal time/place is Tues. 9:30-11:00 in 403 rom.  

<b>Schedule is subject to change, please check frequently. </b>

{% for meeting in site.data.group_meetings %}

<b>{{ meeting.date}}</b>  {{ meeting.presenter}}
<br /> 

{% endfor %}
