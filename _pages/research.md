---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
Under Review
<div class="publications">

{% bibliography --query @*[status=under_review] %}

</div>

In Progress
<div class="publications">
{% bibliography --query @*[status=in_progress] %}
</div>
