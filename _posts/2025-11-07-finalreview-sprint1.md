---
layout: base
title: Sprint 1 - Tools and APIs
description: My first sprint learning development tools and working with APIs
permalink: /finalreviewblog/sprint1/
toc: true
comments: true
---

<style>
body {
  background: #0a0a0a;
  color: #ffffff;
}

.nav-buttons {
  display: flex;
  justify-content: space-between;
  margin: 2.5rem 0;
  gap: 1rem;
  flex-wrap: wrap;
}

.nav-button {
  padding: 0.875rem 1.75rem;
  background: #ffffff;
  color: #0a0a0a;
  text-decoration: none;
  border-radius: 10px;
  font-weight: 600;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(255, 255, 255, 0.2);
  font-size: 0.95rem;
}

.nav-button:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 25px rgba(255, 255, 255, 0.3);
  color: #0a0a0a;
  background: #f0f0f0;
}

.page-header {
  background: linear-gradient(135deg, #1a1a1a 0%, #2d2d2d 100%);
  color: white;
  padding: 2.5rem 2rem;
  border-radius: 16px;
  margin-bottom: 2rem;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
  border: 1px solid #333;
}

.page-header h1 {
  margin: 0;
  font-size: 2.5rem;
  font-weight: 700;
  text-shadow: 0 2px 4px rgba(0,0,0,0.3);
  color: #ffffff;
}

.content-section {
  background: #1a1a1a;
  padding: 2rem;
  border-radius: 12px;
  margin: 2rem 0;
  box-shadow: 0 2px 8px rgba(0,0,0,0.3);
  border-left: 4px solid #4facfe;
  border: 1px solid #333;
}

.content-section h2 {
  color: #ffffff;
  margin-top: 0;
  font-weight: 700;
}

.content-section h3 {
  color: #e0e0e0;
  font-weight: 600;
}

.content-section p, .content-section ul {
  color: #d0d0d0;
  line-height: 1.8;
}

.highlight-box {
  background: #2a2a2a;
  border-left: 5px solid #4facfe;
  padding: 1.75rem;
  border-radius: 10px;
  margin: 2rem 0;
  border: 1px solid #333;
}

.highlight-box strong {
  color: #ffffff;
  font-size: 1.1rem;
}

.highlight-box ul {
  margin: 1rem 0 0 0;
  color: #d0d0d0;
  line-height: 1.8;
}

.project-showcase {
  background: #1a1a1a;
  border: 2px solid #333;
  border-radius: 12px;
  padding: 2rem;
  margin: 2rem 0;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}

.project-showcase h3 {
  color: #4facfe;
  margin-top: 0;
  font-weight: 700;
  font-size: 1.5rem;
}

.project-showcase p, .project-showcase ul {
  color: #d0d0d0;
  line-height: 1.8;
}

.project-showcase strong {
  color: #ffffff;
}

pre {
  background: #0d0d0d;
  padding: 1.5rem;
  border-radius: 10px;
  overflow-x: auto;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
  border: 1px solid #222;
}

code {
  color: #e0e0e0;
  font-family: 'Courier New', monospace;
}

@media (max-width: 768px) {
  .nav-buttons {
    flex-direction: column;
  }
  
  .page-header h1 {
    font-size: 2rem;
  }
}
</style>

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/" class="nav-button">← Back to Overview</a>
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">Next: Sprint 2 →</a>
</div>

<div class="page-header">
  <h1>Sprint 1: Tools and APIs</h1>
</div>

<div class="content-section">
<h2>The Struggle of Getting Started</h2>

<p>At the beginning of the year, I struggled a lot with the setup process and just figuring out what to do. My group at the time was really advanced, and while they worked quickly, I often felt left behind. They didn't really explain what I should be doing, so I had to figure out a lot of things on my own. The worst part was getting my tools to actually work. I kept running into issues with make commands and virtual environments that I didn't know how to fix. Everyone else seemed to have their environment running smoothly while I was stuck troubleshooting for hours.</p>

<div class="highlight-box">
<strong>Initial Challenges:</strong>
<ul>
  <li>Getting make commands to work properly</li>
  <li>Setting up and activating virtual environments</li>
  <li>Understanding what my teammates were doing (they moved fast)</li>
  <li>Learning Git and GitHub basics</li>
  <li>Not really knowing what I should be contributing</li>
</ul>
</div>

<h2>Finding My Role</h2>

<p>Still, I tried to contribute however I could, and once we started working on actual projects, I actually enjoyed it a lot. Even though the setup was frustrating, the coding part was fun.</p>
</div>

<div class="content-section">
<h2>Working with APIs</h2>

<p>One of my first contributions was helping make a lesson on APIs for the class hacks (basically mini lessons we teach each other). I specifically worked on the part about asynchronous functions and the <code>await</code> keyword. It was helpful because teaching something forces you to actually understand it.</p>

<p>After that, I chose to work on an iTunes API project where we took an existing hack and added our own features to it. We added things like:</p>
<ul>
  <li>A search bar that saves your results so you don't lose them</li>
  <li>A feature where you can filter songs by different genres</li>
  <li>Some other small improvements to make it more user-friendly</li>
</ul>

<p>It wasn't anything crazy, but it was one of the first times I felt like I actually built something that worked and did something useful.</p>
</div>

<div class="content-section">
<h2>Understanding Asynchronous Code</h2>

<p>This was probably one of the most useful things I learned in Sprint 1. At first, I didn't get why we couldn't just grab data from an API immediately. But once I understood how asynchronous JavaScript works, it made way more sense:</p>

```javascript
// This doesn't work because fetch returns a promise
let data = fetch('api-url');
console.log(data); // Shows Promise, not the actual data

// This works because we wait for the response
async function getData() {
    let response = await fetch('api-url');
    let data = await response.json();
    console.log(data); // Shows actual data
}
```

<p>Understanding this pattern changed how I thought about coding. It wasn't just about copying examples — it was about actually knowing why things work the way they do.</p>
</div>

<div class="content-section">
<h2>Lessons Learned</h2>

<h3>Technical Skills</h3>
<ul>
  <li>How to work with APIs and handle asynchronous code</li>
  <li>Basic understanding of <code>async</code>, <code>await</code>, and promises</li>
  <li>Using <code>fetch()</code> to get data from external sources</li>
  <li>Debugging when things don't work (which was often)</li>
</ul>

<h3>Soft Skills</h3>
<ul>
  <li><strong>Persistence:</strong> Not giving up even when setup was frustrating</li>
  <li><strong>Figuring things out independently:</strong> Had to google a lot when teammates couldn't help</li>
  <li><strong>Asking questions:</strong> Learned it's better to ask than stay confused</li>
  <li><strong>Teaching others:</strong> Explaining async concepts helped me understand them better</li>
</ul>
</div>

<div class="content-section">
<h2>What I'd Do Differently</h2>

<p>Looking back, I wish I had:</p>
<ul>
  <li>Asked for help earlier with the virtual environment issues instead of wasting time</li>
  <li>Been more assertive about what I should be working on</li>
  <li>Taken better notes on the setup process so I wouldn't forget</li>
  <li>Spent more time understanding Git from the beginning</li>
</ul>

<p>Despite the rough start, this sprint taught me a lot — mostly that struggling through problems is part of learning, and that it's okay to not understand everything immediately.</p>
</div>

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/" class="nav-button">← Back to Overview</a>
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">Next: Sprint 2 →</a>
</div>
