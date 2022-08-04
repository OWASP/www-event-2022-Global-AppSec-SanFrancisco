---

title: Sponsors & Exhibitors
layout: event_noheader
permalink: /sponsors/

---

# {{ page.title }}
We would like to recognize our sponsors and exhibitors: 


{% assign diamonds = site.data.sponsors | where: "type", "Diamond" %}
{% assign golds = site.data.sponsors | where: "type", "Gold" %}
{% assign silvers = site.data.sponsors | where: "type", "Silver" %}


<section class='member'>
<div class='member-wrapper'>
<section class='member-list'>
<h3>Diamond Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in diamonds %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Gold Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in golds %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
<br>
<h3>Silver Sponsors</h3>
<div class='event_member_div'>
{% for sponsor in silvers %}
<a href="{{sponsor.url}}" class="member-logo"><img src="{{sponsor.logo}}" alt="{{sponsor.name}}"></a>
{% endfor %}
</div>
</section>
</div>
</section>
<br><br>
<p>
<hr>