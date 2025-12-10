---

layout: default

title: Blog

---



<h1>Blog Posts</h1>

<ul>

&nbsp; {% for post in site.posts %}

&nbsp;   <li>

&nbsp;     <a href="{{ post.url }}">{{ post.title }}</a>

&nbsp;   </li>

&nbsp; {% endfor %}

</ul>



