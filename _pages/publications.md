---
layout: page
permalink: /research/
title: research
description: publications by categories in reversed chronological order.
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h1>publications</h1>

{% bibliography --file papers.bib %}

<h1>PhD thesis</h1>

{% bibliography --file dissertation.bib %}

<h1>working papers</h1>

{% bibliography --file workingpapers.bib %}

</div>
