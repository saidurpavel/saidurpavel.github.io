---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 1
---

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

  <!--  Journal Section -->
  <div class="pub-section-header" onclick="toggleSection('journal-list')">
     Journal Publications
    <span class="toggle-icon">▾</span>
  </div>
  <div id="journal-list">
    {% bibliography -f papers -q @*[category=journal]* %}
  </div>

  <!--  Conference Section -->
  <div class="pub-section-header" onclick="toggleSection('conference-list')">
     Conference Publications
    <span class="toggle-icon">▾</span>
  </div>
  <div id="conference-list">
    {% bibliography -f papers -q @*[category=conference]* %}
  </div>

</div>

<script>
function toggleSection(id) {
  const section = document.getElementById(id);
  const icon = section.previousElementSibling.querySelector('.toggle-icon');
  if (section.style.display === 'none') {
    section.style.display = 'block';
    icon.textContent = '▾';
  } else {
    section.style.display = 'none';
    icon.textContent = '▸';
  }
}
</script>
