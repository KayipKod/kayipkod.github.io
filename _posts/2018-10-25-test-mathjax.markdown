---
layout: post
title: "How to use MathJax"
date: 2018-10-25 12:47:08 +0300
categories: jekyll
---

{%- include mathjax.html -%}

$ J(x) = \int{L(t, x, \dot{x}) dt} \$

Just include the following line in your post:
{% raw %}
{%- include mathjax.html -%}
{% endraw %}

and you can use [MathJax syntax](https://www.mathjax.org/)
