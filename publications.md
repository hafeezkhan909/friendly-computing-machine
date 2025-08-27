---
layout: default
title: Publications
permalink: /publications/
---

<h1>Publications</h1>
<p>Publications by year (reverse chronological). Powered by jekyll-scholar.</p>

<input id="pub-filter" type="text" placeholder="Type to filter" oninput="filterPubs()">

{% bibliography --group_by year --group_order descending %}
