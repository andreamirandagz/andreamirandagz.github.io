---
layout: page
permalink: /publications/
title: publications
description:
nav: true
---

<div class="publications">

<h2 class="year">Peer-reviewed publications</h2>
{% bibliography -f papers -q @article %}

<h2 class="year">Manuscripts under review</h2>
{% bibliography -f papers -q @unpublished[status=review]* %}

<h2 class="year">Manuscripts in preparation</h2>
{% bibliography -f papers -q @unpublished[status=prep]* %}

</div>