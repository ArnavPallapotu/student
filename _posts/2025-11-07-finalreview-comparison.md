---
layout: base
title: Then vs Now - My Growth
description: Comparing my skills and understanding from the beginning of the year to now
permalink: /finalreview/comparison
toc: true
comments: true
---

<style>
.nav-buttons {
  display: flex;
  justify-content: space-between;
  margin: 2rem 0;
  gap: 1rem;
}

.nav-button {
  padding: 0.75rem 1.5rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  text-decoration: none;
  border-radius: 8px;
  font-weight: 500;
  transition: all 0.3s ease;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.nav-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 12px rgba(0,0,0,0.15);
}

.comparison-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  margin: 2rem 0;
}

.comparison-card {
  background: #f7fafc;
  border-radius: 12px;
  padding: 2rem;
  border-left: 4px solid #667eea;
}

.comparison-card.now {
  border-left-color: #48bb78;
}

.comparison-card h3 {
  margin-top: 0;
  color: #2d3748;
}

.comparison-card ul {
  color: #4a5568;
  line-height: 1.8;
}

@media (max-width: 768px) {
  .comparison-grid {
    grid-template-columns: 1fr;
  }
  
  .nav-buttons {
    flex-direction: column;
  }
}
</style>

<div class="nav-buttons">
  <a href="/finalreviewblog" class="nav-button">← Back to Overview</a>
  <a href="/finalreview/sprint1" class="nav-button">Next: Sprint 1 →</a>
</div>

# Then vs Now: My Growth as a CS Student

## Reflecting on My Journey

When I first started this course, I had no idea what to expect. I knew a little bit about coding from some online tutorials, but actually working in a real development environment was completely different. Looking back now, I can see how much I've grown — not just in coding skills, but in problem-solving, teamwork, and understanding how software development actually works.

---

<div class="comparison-grid">
  <div class="comparison-card then">
    <h3>At the Beginning</h3>
    <ul>
      <li><strong>Struggled with setup:</strong> Getting tools like VSCode, GitHub, and local servers running was confusing</li>
      <li><strong>Limited coding knowledge:</strong> Knew some Python basics but nothing about web development</li>
      <li><strong>Worked alone:</strong> Preferred doing things by myself because group work felt awkward</li>
      <li><strong>Overwhelmed easily:</strong> When things broke, I didn't know where to start debugging</li>
      <li><strong>Focused on "just finishing":</strong> Cared more about getting it done than understanding why it worked</li>
    </ul>
  </div>

  <div class="comparison-card now">
    <h3>Now</h3>
    <ul>
      <li><strong>Comfortable with tools:</strong> Can set up environments, use Git confidently, and troubleshoot issues</li>
      <li><strong>Full-stack understanding:</strong> Know how frontend connects to backend, how APIs work, and can build complete features</li>
      <li><strong>Value teamwork:</strong> Understand that collaboration makes projects better and helps me learn faster</li>
      <li><strong>Debug systematically:</strong> Use console logs, read error messages carefully, and test incrementally</li>
      <li><strong>Focus on quality:</strong> Care about code organization, user experience, and why things work the way they do</li>
    </ul>
  </div>
</div>

---

## Key Turning Points

### Understanding Asynchronous Code
One of the biggest "aha" moments was finally understanding how `async` and `await` work in JavaScript. At first, promises and asynchronous functions seemed like magic, but once I understood the concept of waiting for data to load before displaying it, everything clicked. This was crucial for working with APIs.

### Learning to Ask for Help
Early on, I was too embarrassed to ask questions when I didn't understand something. But after struggling alone for hours on problems that teammates could have helped with in minutes, I realized that asking questions is actually a sign of wanting to learn, not weakness.

### Appreciating Good Documentation
I used to skip over documentation and just try to guess how things worked. Now I realize that reading docs carefully saves so much time and helps me understand tools deeply instead of just memorizing syntax.

---

## What This Growth Means

The biggest change isn't just that I can code better — it's that I *think* differently about problems. I can break down complex features into smaller tasks, anticipate where bugs might happen, and communicate technical ideas to teammates. I'm not afraid of error messages anymore; I see them as clues instead of roadblocks.

---

<div class="nav-buttons">
  <a href="/finalreviewblog" class="nav-button">← Back to Overview</a>
  <a href="/finalreview/sprint1" class="nav-button">Next: Sprint 1 →</a>
</div>
