---
layout: base
title: Final Review Project
description: My experiences throughout the trimester and everything I have learned and accomplished.
permalink: /finalreviewblog/
toc: false
comments: true
---

<style>
body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
  background: #0a0a0a;
  color: #ffffff;
}

.intro-section {
  background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
  color: white;
  padding: 3rem 2rem;
  border-radius: 16px;
  margin-bottom: 3rem;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
  border: 1px solid #333;
}

.intro-section h1 {
  margin-top: 0;
  font-size: 2.5rem;
  font-weight: 700;
  text-shadow: 0 2px 4px rgba(0,0,0,0.3);
  color: #ffffff;
}

.intro-section p {
  font-size: 1.1rem;
  line-height: 1.7;
  opacity: 0.95;
  color: #e0e0e0;
}

.section-header {
  text-align: center;
  margin: 3rem 0 2rem 0;
}

.section-header h2 {
  font-size: 2rem;
  color: #ffffff;
  margin-bottom: 0.5rem;
  font-weight: 700;
}

.section-header p {
  color: #b0b0b0;
  font-size: 1.1rem;
}

.topic-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  margin: 2rem 0 3rem 0;
}

.topic-card {
  background: #1a1a1a;
  border: 2px solid #333;
  border-radius: 16px;
  padding: 2.5rem 2rem;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  text-decoration: none;
  color: #ffffff;
  display: block;
  box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  position: relative;
  overflow: hidden;
}

.topic-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 5px;
  background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%);
  transform: scaleX(0);
  transition: transform 0.3s ease;
  transform-origin: left;
}

.topic-card:hover::before {
  transform: scaleX(1);
}

.topic-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 20px 40px rgba(79, 172, 254, 0.3);
  border-color: #4facfe;
  background: #222;
}

.topic-card h3 {
  margin-top: 0;
  color: #ffffff;
  font-size: 1.6rem;
  font-weight: 700;
  border: none;
  padding: 0;
  margin-bottom: 0;
}

.conclusion-section {
  background: #1a1a1a;
  border-left: 5px solid #4facfe;
  padding: 2.5rem;
  border-radius: 12px;
  margin-top: 3rem;
  box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  border: 1px solid #333;
}

.conclusion-section h2 {
  color: #ffffff;
  margin-top: 0;
  font-weight: 700;
}

.conclusion-section p {
  color: #e0e0e0;
  line-height: 1.8;
  font-size: 1.05rem;
}

@media (max-width: 768px) {
  .topic-grid {
    grid-template-columns: 1fr;
  }
  
  .intro-section h1 {
    font-size: 2rem;
  }
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
  <a href="{{ site.baseurl }}/finalreviewblog/sprint1" class="topic-card">
    <h3>Sprint 1</h3>
  </a>

  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="topic-card">
    <h3>Sprint 2</h3>
  </a>

  <a href="{{ site.baseurl }}/finalreviewblog/sprint3" class="topic-card">
    <h3>Sprint 3</h3>
  </a>

  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="topic-card">
    <h3>Night at the Museum</h3>
  </a>

  <a href="{{ site.baseurl }}/finalreviewblog/future" class="topic-card">
    <h3>Future</h3>
  </a>

  <a href="{{ site.baseurl }}/finalreviewblog/cool-stuff" class="topic-card">
    <h3>Cool Stuff</h3>
  </a>
</div>

<div class="conclusion-section">
  <h2>Conclusion</h2>
  <p>This year really taught me a lot — not just about programming, but about working with people, staying organized, and learning how to keep improving. At the start, I struggled to even get things set up, and now I can confidently build projects, explain concepts, and collaborate effectively. I still have a lot to learn, but I feel like I've built a solid foundation to keep going from here.</p>
</div>
