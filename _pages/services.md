---
layout: page
permalink: /services/
title: Services
description: Overview of my academic and professional services.
nav: true
nav_order: 3
---

<div class="publication-toggles">

<!-- Section 1: Paper Reviews -->
<div class="pub-section-header" onclick="toggleSection('reviews')">
  📄 Paper Reviews
  <span class="toggle-icon">▾</span>
</div>
<div id="reviews">
  <h4>Journal Review</h4>
  <ul>
    <li>IEEE Transactions on Signal Processing</li>
    <li>Elsevier Signal Processing</li>
    <li>IEEE Access</li>
    <!-- Add more as needed -->
  </ul>

  <h4>Conference Review</h4>
  <ul>
    <li>IEEE ICASSP</li>
    <li>IEEE SPAWC</li>
    <li>Asilomar Conference</li>
    <!-- Add more as needed -->
  </ul>
</div>

<!-- Section 2: Courses Taught -->
<div class="pub-section-header" onclick="toggleSection('courses')">
  🎓 Courses Taught
  <span class="toggle-icon">▾</span>
</div>
<div id="courses">
  <h4>At Temple University</h4>
  <ul>
    <li>ECE 4513: Digital Communication Systems Lab</li>
    <li>ECE 2113: Electrical Devices & Systems I Lab</li>
    <li>ECE 1111: Engineering Computation I Lab</li>
    <li>ECE 3313: Microelectronics I Lab</li>
    <li>ECE 2333: Principles of Electric Circuits Lab</li>
    <li>ECE 2332: Principles of Electric Circuits</li>
    <li>ECE 3512: Signals and Systems</li>
  </ul>

  <h4>At Premier University</h4>
  <ul>
    <li>Control Systems</li>
    <li>Control Systems Lab</li>
    <li>Electronics 1</li>
    <li>Electronics 1 Lab</li>
    <li>Electrical Circuits 1</li>
    <li>Electrical Circuits 1 Lab</li>
    <li>Microprocessor & Microcontroller</li>
  </ul>
</div>

<!-- Section 3: Professional Memberships -->
<div class="pub-section-header" onclick="toggleSection('memberships')">
  👥 Professional Memberships
  <span class="toggle-icon">▾</span>
</div>
<div id="memberships">
  <ul>
    <li>IEEE Member</li>
    <li>IEEE Signal Processing Society Member</li>
    <li>ACM Professional Member</li>
    <!-- Add more as needed -->
  </ul>
</div>

</div>

<script>
function toggleSection(id) {
  const section = document.getElementById(id);
  const icon = section.previousElementSibling.querySelector('.toggle-icon');
  if (section.style.display === 'none' || section.style.display === '') {
    section.style.display = 'block';
    icon.textContent = '▾';
  } else {
    section.style.display = 'none';
    icon.textContent = '▸';
  }
}
</script>
