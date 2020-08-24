---
permalink: /
title: "Home"
excerpt: "Home"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am Felipe Pérez, a fourth year PhD student of the University of Bristol under the supervision of [Thomas Jordan](https://people.maths.bris.ac.uk/~matmj/). My main interests are Ergodic Theory and its relationship with Dimension Theory. I did my undergraduate and masters degree at Pontificia Universidad Católica de Chile under the supervision of [Godofredo Iommi](http://www.mat.uc.cl/~giommi/). During the (calendar) year 2019 I visited Professor [Matt Nicol](https://www.math.uh.edu/~nicol/) in the University of Houston, Texas. On the mobile version of this site, click on the three parallel lines button on the top right to display the menu.

![venice](/files/venice.jpg)

Me in Venice, Italy during the [Workshop on Hyperbolic Dynamics 2017](http://indico.ictp.it/event/7970) at ICTP.


<h2>Latest Post</h2>

<ul>
  {% for post in site.posts limit:1 %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


