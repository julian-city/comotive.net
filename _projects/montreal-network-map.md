---
layout: project
title: "Montréal Network Map"
description: "Coming soon."
tags: [transit, GIS, Montréal]
---

A first look at our mapping work in Montréal. Project details coming soon.

<div id="map" style="height: 400px; border-radius: 6px; border: 1px solid #B1CAD1;"></div>
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css"/>
<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
<script>
  var map = L.map('map').setView([45.508, -73.554], 12); // Montréal
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; OpenStreetMap contributors'
  }).addTo(map);
</script>
