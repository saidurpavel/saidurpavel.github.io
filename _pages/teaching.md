---
layout: page
permalink: /teaching/
title: Teaching
description: I worked as a Teaching Assistant (TA) at Temple University from 2022 to 2023, and prior to that, I worked as a Lecturer at Premier University, Chittagong, from 2018 to 2020.
nav: true
nav_order: 4
---

<div class="publication-toggles">

  <!-- Temple Section -->
  <div class="pub-section-header" onclick="toggleSection('temple-list')">
    Courses Taught at Temple University
    <span class="toggle-icon">▾</span>
  </div>
  <div id="temple-list">
    <ul>
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%204513" target="_blank">ECE 4513: Digital Communication Systems Lab.</a></li>
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%202113" target="_blank">ECE 2113: Electrical Devices & Systems I Lab.</a></li>
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%201111" target="_blank">ECE 1111: Engineering Computation I Lab.</a></li>       
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%203313" target="_blank">ECE 3313: Microelectronics I Lab.</a></li>    
    </ul>     
     <li><a href="https://bulletin.temple.edu/search/?P=ECE%202333" target="_blank">ECE 2333: Principles of Electric Circuits Lab.</a></li>    
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%202332" target="_blank">ECE 2333: Principles of Electric Circuits.</a></li>      
       <li><a href="https://bulletin.temple.edu/search/?P=ECE%203512" target="_blank">ECE 3512: Signals and Systems</a></li>  
    </ul>
  </div>

  <!-- Premier Section -->
  <div class="pub-section-header" onclick="toggleSection('premier-list')">
     Courses Taught at Premier University
    <span class="toggle-icon">▾</span>
  </div>
  <div id="premier-list">
    <ul>
      <li><a href="#">EEE 3112: Communication Engineering</a></li>
      <li><a href="#">EEE 2211: Signals and Linear Systems</a></li>
      <li><a href="#">EEE 4314: Digital Image Processing</a></li>
      <li><a href="#">EEE 4413: Wireless Communication</a></li>
      <li><a href="#">EEE 1011: Electrical Circuits I</a></li>
    </ul>
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

