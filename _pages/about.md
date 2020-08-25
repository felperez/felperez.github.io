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


<h2>Latest blog post</h2>

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title}}</a>, published on {{post.date | date: "%-d %B %Y"}}</h3></li>
  {% endfor %}
</ul>


<h2>Pictures</h2>


<html>
<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}
</style>
</head>
<body>


<div class="row">
  <div class="column">
    <img src="/files/pictures/venice.jpg" alt="Me in Venice" style="width:100%">
  </div>
  <div class="column">
    <img src="/files/pictures/stockholm.jpg" alt="Me in Stockholm" style="width:100%">
  </div>
  <div class="column">
    <img src="/files/pictures/edinburgh.jpg" alt="Edinburgh" style="width:100%">
  </div>
</div>

</body>
</html>



<img src="/files/pictures/venice.jpg" class="img" alt="" width="200" height="150">


.img:hover{
    color: #424242; 
  -webkit-transition: all .3s ease-in;
  -moz-transition: all .3s ease-in;
  -ms-transition: all .3s ease-in;
  -o-transition: all .3s ease-in;
  transition: all .3s ease-in;
  opacity: 1;
  transform: scale(1.15);
  -ms-transform: scale(1.15); /* IE 9 */
  -webkit-transform: scale(1.15); /* Safari and Chrome */

}

