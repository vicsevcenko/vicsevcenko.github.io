---
layout: page
permalink: /research/
title: research
description: Published articles, papers under review, and working papers.
nav: true
nav_order: 1
---

{% include bib_search.liquid %}

<div class="publications">

## Published

{% bibliography --query "@article" %}

---

## Under Review, Working Papers, and Work in Progress

{% bibliography --query "@unpublished" %}

</div>
