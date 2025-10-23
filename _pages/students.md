---
layout: page
title: students
permalink: /students/
description: Current and former students
nav: true
nav_order: 5
---

<style>
.student-section {
  margin-bottom: 3rem;
}

.student-section h2 {
  font-size: 1.5rem;
  font-weight: 500;
  margin-bottom: 1.5rem;
  color: var(--global-text-color);
  border-bottom: 1px solid var(--global-divider-color);
  padding-bottom: 0.5rem;
}

.student-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 2rem;
  margin-bottom: 2rem;
}

.student-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 1.5rem;
  background: var(--global-bg-color);
  border-radius: 8px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.student-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
}

.student-photo {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
  border: 3px solid var(--global-divider-color);
}

.student-name {
  font-size: 1.1rem;
  font-weight: 500;
  margin-bottom: 0.25rem;
  color: var(--global-text-color);
}

.student-info {
  font-size: 0.9rem;
  color: var(--global-text-color-light);
  margin-bottom: 0.5rem;
}

.student-links {
  display: flex;
  gap: 0.75rem;
  margin-top: 0.5rem;
}

.student-links a {
  color: var(--global-theme-color);
  font-size: 0.9rem;
  text-decoration: none;
  transition: opacity 0.2s ease;
}

.student-links a:hover {
  opacity: 0.7;
}
</style>

<div class="students-page">

  <div class="student-section">
    <h2>PhD Students</h2>
    <div class="student-grid">
      <!-- Example PhD student - replace with actual students -->
      <div class="student-card">
        <div class="student-name">Student Name</div>
        <div class="student-info">PhD Candidate</div>
        <div class="student-info">Research Area</div>
        <div class="student-links">
          <a href="#" target="_blank">Website</a>
        </div>
      </div>
    </div>
  </div>

  <div class="student-section">
    <h2>MA Students</h2>
    <div class="student-grid">
      <!-- Example MA student - replace with actual students -->
      <div class="student-card">
        <div class="student-name">Student Name</div>
        <div class="student-info">MA Student</div>
        <div class="student-info">Research Area</div>
        <div class="student-links">
          <a href="#" target="_blank">Website</a>
        </div>
      </div>
    </div>
  </div>

  <div class="student-section">
    <h2>Former Students</h2>
    <div class="student-grid">
      <!-- Example former student - replace with actual students -->
      <div class="student-card">
        <div class="student-name">Former Student Name</div>
        <div class="student-info">PhD, Year</div>
        <div class="student-info">Current Position</div>
        <div class="student-links">
          <a href="#" target="_blank">Website</a>
        </div>
      </div>
    </div>
  </div>

</div>
