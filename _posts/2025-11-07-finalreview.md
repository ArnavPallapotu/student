---
layout: base
title: Final Review Project
description: My experiences throughout the trimester and everything I have learned and accomplished.
permalink: /finalreviewblog
toc: false
comments: true
---

<style>
body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
}

.intro-section {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 3rem 2rem;
  border-radius: 12px;
  margin-bottom: 3rem;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
}

.intro-section h1 {
  margin-top: 0;
  font-size: 2.5rem;
  font-weight: 700;
}

.intro-section p {
  font-size: 1.1rem;
  line-height: 1.6;
  opacity: 0.95;
}

.section-header {
  text-align: center;
  margin: 3rem 0 2rem 0;
}

.section-header h2 {
  font-size: 2rem;
  color: #2d3748;
  margin-bottom: 0.5rem;
}

.section-header p {
  color: #718096;
  font-size: 1.1rem;
}

.topic-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.topic-card {
  background: white;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  padding: 2rem;
  transition: all 0.3s ease;
  text-decoration: none;
  color: inherit;
  display: block;
  box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  position: relative;
  overflow: hidden;
}

.topic-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 4px;
  background: linear-gradient(90deg, #667eea 0%, #764ba2 100%);
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.topic-card:hover::before {
  transform: scaleX(1);
}

.topic-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 24px rgba(0,0,0,0.15);
  border-color: #667eea;
}

.topic-card h3 {
  margin-top: 0;
  color: #2d3748;
  font-size: 1.5rem;
  font-weight: 600;
  border: none;
  padding: 0;
  margin-bottom: 0.75rem;
}

.topic-card p {
  margin-bottom: 0;
  color: #718096;
  line-height: 1.6;
}

.conclusion-section {
  background: #f7fafc;
  border-left: 4px solid #667eea;
  padding: 2rem;
  border-radius: 8px;
  margin-top: 3rem;
}

.conclusion-section h2 {
  color: #2d3748;
  margin-top: 0;
}

.conclusion-section p {
  color: #4a5568;
  line-height: 1.8;
  font-size: 1.05rem;
}
</style>

<div class="intro-section">
  <h1>Final Review Project</h1>
  <p>Looking back at this year, I can definitely say I've changed a lot as a computer science student. At the start, I was honestly pretty lost, especially during the first few weeks when we were setting up our tools and learning how everything worked. But as the months went on, I started understanding not just how to code, but also how to work with others and how much organization matters in a team project.</p>
  <p>This review is organized into different topics covering my journey throughout the trimester. Click on any card below to explore that topic.</p>
</div>

<div class="section-header">
  <h2>Review Topics</h2>
  <p>Explore my journey through different aspects of the course</p>
</div>

<div class="topic-grid">
  <a href="/finalreviewblog/sprint1" class="topic-card">
    <h3>Sprint 1: Tools & APIs</h3>
    <p>Learning the basics and working with APIs</p>
  </a>

  <a href="/finalreviewblog/sprint2" class="topic-card">
    <h3>Sprint 2: Fundamentals</h3>
    <p>Python, JavaScript, and teamwork</p>
  </a>

  <a href="/finalreviewblog/sprint3" class="topic-card">
    <h3>Sprint 3: Digital Famine</h3>
    <p>Building the final project</p>
  </a>

  <a href="/finalreviewblog/natm" class="topic-card">
    <h3>Night at the Museum</h3>
    <p>Presenting our work and getting feedback</p>
  </a>

  <a href="/finalreviewblog/future" class="topic-card">
    <h3>What's Next</h3>
    <p>Future project ideas and learning goals</p>
  </a>
</div>

<div class="conclusion-section">
  <h2>Conclusion</h2>
  <p>This year really taught me a lot, not just about programming, but about working with people, staying organized, and learning how to keep improving. At the start, I struggled to even get things set up, and now I can confidently build projects, explain concepts, and collaborate effectively. I still have a lot to learn, but I feel like I've built a solid foundation to keep going from here.</p>
</div>
