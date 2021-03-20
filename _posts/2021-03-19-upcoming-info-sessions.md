---
title: Spring 2021 Ph.D. Information Sessions
author: Steven Swanson
category: info-session
tags: ['info-session']
redirect_from:  /upcoming-sessions
---

We have two live information sessions coming up in April.  They will be held on
Zoom.  Each will have two parallel "tracks" focused on different aspects
getting a Ph.D.

| Date/Time                | Topics                     |
|--------------------------|----------------------------|
| April 13, 12:30-1:30 PDT | Ph.D. Student Life         |
|                          | What is Research?          |
| April 21, 12:00-1:00 PDT | Applying to Ph.D. Programs |
|                          | Should I get a Ph.D.?      |

You don't need to choose a track, you'll be able to freely switch back and
forth.

You can register [here]().  It's free!


Before attending, it please checkout the [FAQ]({{ site.baseurl }}/2_wiki.html).

{% assign t = site.data._2021_sp_panelist_metadata | sort:"last" %}

# Organizers

<table>
<colgroup>
<col span="1" style="width: 20%"/>
<col span="1" style="width: 80%"/>
</colgroup>
{% for p in t %}
{% if p.type == 'org' %}
<tr>
{% if p.photo != nil %}
<td>
{% if p.homepage != nil %}
<a href="{{p.homepage}}">
{% endif %}
<img src="{{p.photo}}" style="width: 100px"/>
{% if p.homepage != nil %}
</a>
{% endif %}
</td>
{% else %}
<td></td>
{% endif %}
<td>
<div>
{% if p.homepage != nil %}
<a href="{{p.homepage}}">
{% endif %}
{{ p.first }} {{p.last}}{% if p.homepage != nil %}</a>{% endif %}, {{ p.org }} ({{p.area}})</div><div style="font-size: small">{{p.bio}}</div></td>
</tr>
{% endif %}
{% endfor %}
</table>


# Panelists

## Students

<table>
<colgroup>
<col span="1" style="width: 20%"/>
<col span="1" style="width: 80%"/>
</colgroup>
{% for p in t %}
{% if p.type == 'Ph.D. Student' %}
<tr>
{% if p.photo != nil %}
<td>
{% if p.homepage != nil %}
<a href="{{p.homepage}}">
{% endif %}
<img src="{{p.photo}}" style="width: 100px"/>
{% if p.homepage != nil %}
</a>
{% endif %}
</td>
{% else %}
<td></td>
{% endif %}
<td>
<div>
{% if p.homepage != nil %}
<a href="{{p.homepage}}">
{% endif %}
{{ p.first }} {{p.last}}{% if p.homepage != nil %}</a>{% endif %}, {{ p.org }} ({{p.area}})</div><div style="font-size: small">{{p.bio}}</div></td>
</tr>
{% endif %}
{% endfor %}
</table>



## Faculty

<table>
<colgroup>
<col span="1" style="width: 20%"/>
<col span="1" style="width: 80%"/>
</colgroup>
{% for p in t %}
{% if p.type == 'Professor' %}
<tr>
{% if p.photo != nil %}
<td>
{% if p.homepage != nil %}
<a href="{{p.homepage}}">
{% endif %}
<img src="{{p.photo}}" style="width: 100px"/>
{% if p.homepage != nil %}
</a>
{% endif %}
</td>
{% else %}
<td></td>
{% endif %}
<td>
<div>
{% if p.homepage != nil %}
<a href="{{p.homepage}}">
{% endif %}
{{ p.first }} {{p.last}}{% if p.homepage != nil %}</a>{% endif %}, {{ p.org }} ({{p.area}})</div><div style="font-size: small">{{p.bio}}</div></td>
</tr>
{% endif %}
{% endfor %}
</table>
