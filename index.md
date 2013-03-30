---
layout: page
title: Collaborative technological watch
tagline: Qualification and Selection of Opensource Software
---
{% include JB/setup %}

![QSOS logo](https://raw.github.com/drakkr/QSOS/master/Method/fr/Images/QSOS-small.png)

### Impatient?

Jump directly to the _Open Source Selection Software_ portal (O3S):

* [Master](http://o3s.qsos.org/master/): official instance (validated by the QSOS community)

* [Incoming](http://o3s.qsos.org/icoming/): sandbox instance (everybody can contribute evaluations)

### Recent news

<ul class="posts">
  {% for post in site.posts limit: 5 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

### But... what is QSOS anyway?
  
QSOS is a free project aiming to mutualize and capitalize technological watch on open source components and projects.

It is part of the [drakkr](http://www.drakkr.org) framework for open source governance.

<br/>  
<div>
  <a href="Method.html"> <img src="images/monkey-iwazaru-learn.png"/> </a> 
  <a href="Tools.html"> <img src="images/monkey-kikazaru-use.png"/> </a> 
  <a href="Community.html"> <img src="images/monkey-mizaru-share.png"/> </a>  
</div>
<br/>  

It is composed of:

* A formal [method](/Method.html) describing a workflow to evaluate open source components and related projects

* A set of [tools](/Tools.html) to help apply the QSOS workflow on templates, evaluations and comparisons

* A [community](/Community.html) developping and maintaining these templates, evaluations and tools

