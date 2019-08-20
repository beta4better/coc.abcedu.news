---
layout: default
title: Charles' Lab
tagline: rebuild from 2016
---

<table>
<tr>
    <th>排名</th>
    <th>姓名</th>
    <th>奖杯</th>
    <th>捐兵</th>
    <th>收兵</th>
</tr>

{% for member in site.data.clans-22YUYU2P9.memberList %}
<tr>
    <td>{{ member.clanRank }}</td>
    <td>{{ member.name }}</td>
    <td><img src="{{ member.league.iconUrls.small }}" /></td>
    <td>{{ member.donations }}</td>
    <td>{{ member.donationsReceived }}</td>
</tr>
{% endfor %}
  

{% include JB/setup %}
