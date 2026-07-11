---
layout: project
title: "Project 1"
description: "Coming soon."
tags: [transit, GIS, Montreal]
---

Here is where we will highlight our projects.

<div id="map" style="height: 400px;"></div>
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css"/>
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
<script>
  var map = L.map('map').setView([45.508, -73.554], 12); // Montreal
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png').addTo(map);
</script>