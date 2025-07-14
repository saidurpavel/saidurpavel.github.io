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
   Paper Reviews
  <span class="toggle-icon">▾</span>
</div>
  <p>
    I have contributed as a peer reviewer for several prestigious journals and conferences. Below is a categorized list of my reviewing activities.
  </p>
<div id="reviews">
  <h4>Journal Review</h4>
  <ul>
    <li>Signal Processing</li>
    <li>IEEE Signal Processing Letters</li>
  </ul>

  <h4>Conference Review</h4>
  <ul>
    <li>IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</li>
    <li>Asilomar Conference on Signals, Systems & Computers</li>
    <li>IEEE Signal Processing in Medicine and Biology Symposium</li>
    <!-- Add more as needed -->
  </ul>
</div>

<!-- Section 2: Courses Taught -->
<div class="pub-section-header" onclick="toggleSection('courses')">
   Courses Taught
  <span class="toggle-icon">▾</span>
</div>
<p>
I worked as a Teaching Assistant (TA) at Temple University from 2022 to 2023, and prior to that, I worked as a Lecturer at Premier University, Chittagong, from 2018 to 2020.
</p>
<div id="courses">
  <h4>Temple University</h4>
  <ul>
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%204513" target="_blank">ECE 4513: Digital Communication Systems Lab.</a></li>
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%202113" target="_blank">ECE 2113: Electrical Devices & Systems I Lab.</a></li>
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%201111" target="_blank">ECE 1111: Engineering Computation I Lab.</a></li>       
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%203313" target="_blank">ECE 3313: Microelectronics I Lab.</a></li>        
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%202333" target="_blank">ECE 2333: Principles of Electric Circuits Lab.</a></li>    
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%202332" target="_blank">ECE 2333: Principles of Electric Circuits.</a></li>      
      <li><a href="https://bulletin.temple.edu/search/?P=ECE%203512" target="_blank">ECE 3512: Signals and Systems</a></li>  
  </ul>

  <h4> Premier University</h4>
  <ul>
        <li>EEE 101: Electrical Circuits 1</li>
        <li>EEE 102: Electrical Circuits 1 Lab.</li>    
        <li>EEE 211: Electronics 1</li>
        <li>EEE 212: Electronics 1 Lab.</li>    
        <li>EEE 313: Control Systems</li>
        <li>EEE 314: Control Systems Lab.</li>
         <li>EEE 371: Microprocessor & Microcontroller</li>
  </ul>
</div>

<!-- Section 3: Professional Memberships -->
<div class="pub-section-header" onclick="toggleSection('memberships')">
   Professional Memberships
  <span class="toggle-icon">▾</span>
</div>
<div id="memberships">
  <ul>
    <li>IEEE Signal Processing Society</li>
    <li>IEEE Eta Kappa Nu Honors Society</li> 
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
