---
layout: home
title: 花谢花开 潮起潮落
tagline: 部落捐收无要求，竞赛每人至少500。捐兵一千，满竞赛，对位三星长老。援兵三十分钟内按要求，过后随意补，部落战除外。部落战每周四六上午开，不参战挂红，参战挂绿并加群874577443。
---

<div class="page-header">
    <h1> {{ site.data.clans-22YUYU2P9.name }} </h1>
</div>
<div class="jumbotron">
    <p> {{ site.data.clans-22YUYU2P9.description }} </p>
</div>

<div class="row">
<table class="table" >
<thread>
<tr>
    <th>#</th>
    <th></th>
    <th>Tag</th>
    <th>Name</th>
    <th>Role</th>
    <th>Level</th>
    <th>Trophies</th>
    <th>Versus Trophies</th>
    <th>Donations</th>
    <th>Donations Received</th>
</tr>
</thread>

<tbody>
{% for member in site.data.clans-22YUYU2P9.memberList %}
<tr>
    <td>{{ member.clanRank }}</td>
    <td>{{ member.badgeUrls.small }}</td>
    <td>{{ member.tag }}</td>
    <td>{{ member.name }}</td>
    <td>{{ member.role | replace: "leader","首领" | replace: "coLeader","副首领" | replace: "admin","长老" | replace: "member","成员" }}</td>
    <td>{{ member.expLevel }}</td>
    <td>{{ member.trophies}}</td>
    <td>{{ member.versusTrophies}}</td>
    <td>{{ member.donations }}</td>
    <td>{{ member.donationsReceived }}</td>
</tr>
{% endfor %}
</tbody>
</table>
</div>


<div class="page-header">
    <h1> {{ site.data.clans-28CYG9JJR.name }} </h1>
</div>
<div class="jumbotron">
    <p> {{ site.data.clans-28CYG9JJR.description }} </p>
</div>
<div class="row">
<table class="table" >
<thread>
<tr>
    <th>#</th>
    <th></th>
    <th>Tag</th>
    <th>Name</th>
    <th>Role</th>
    <th>Level</th>
    <th>Trophies</th>
    <th>Versus Trophies</th>
    <th>Donations</th>
    <th>Donations Received</th>
</tr>
</thread>

<tbody>
{% for member in site.data.clans-28CYG9JJR.memberList %}
<tr>
    <td>{{ member.clanRank }}</td>
    <td>{{ member.badgeUrls.small }}</td>
    <td>{{ member.tag }}</td>
    <td>{{ member.name }}</td>
    <td>{{ member.role | replace: "leader","首领" | replace: "coLeader","副首领" | replace: "admin","长老" | replace: "member","成员" }}</td>    <td>{{ member.expLevel }}</td>
    <td>{{ member.trophies}}</td>
    <td>{{ member.versusTrophies}}</td>
    <td>{{ member.donations }}</td>
    <td>{{ member.donationsReceived }}</td>
</tr>
{% endfor %}
</tbody>
</table>
</div>


<div class="page-header">
    <h1> {{ site.data.clans-28QPLY9R8.name }} </h1>
</div>
<div class="jumbotron">
    <p> {{ site.data.clans-28QPLY9R8.description }} </p>
</div>
<div class="row">
<table class="table" >
<thread>
<tr>
    <th>#</th>
    <th></th>
    <th>Tag</th>
    <th>Name</th>
    <th>Role</th>
    <th>Level</th>
    <th>Trophies</th>
    <th>Versus Trophies</th>
    <th>Donations</th>
    <th>Donations Received</th>
</tr>
</thread>

<tbody>
{% for member in site.data.clans-28QPLY9R8.memberList %}
<tr>
    <td>{{ member.clanRank }}</td>
    <td>{{ member.badgeUrls.small }}</td>
    <td>{{ member.tag }}</td>
    <td>{{ member.name }}</td>
    <td>{{ member.role | replace: "leader","首领" | replace: "coLeader","副首领" | replace: "admin","长老" | replace: "member","成员" }}</td>
    <td>{{ member.expLevel }}</td>
    <td>{{ member.trophies}}</td>
    <td>{{ member.versusTrophies}}</td>
    <td>{{ member.donations }}</td>
    <td>{{ member.donationsReceived }}</td>
</tr>
{% endfor %}
</tbody>
</table>
</div>

<div class="alert alert-info" role="alert">
       Updated on <strong>2019.8.20</strong>
</div>


{% include JB/setup %}
