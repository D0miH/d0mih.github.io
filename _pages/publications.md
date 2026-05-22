---
layout: page
permalink: /publications/
title: publications
description: <em>*</em> denotes equal contribution and joint lead authorship
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{% bibliography --query @* --sort_by year,month --order descending --group_by year --group_order descending -f {{ site.scholar.bibliography }} %}

</div>
