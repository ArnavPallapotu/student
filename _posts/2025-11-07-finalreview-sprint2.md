---
layout: base
title: Sprint 2 - Fundamentals
description: Learning Python, JavaScript fundamentals, and the importance of teamwork
permalink: /finalreviewblog/sprint2/
toc: true
comments: true
---

<style>
body {
  background: #f8f9fa;
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
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  color: white;
  text-decoration: none;
  border-radius: 10px;
  font-weight: 600;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(79, 172, 254, 0.3);
  font-size: 0.95rem;
}

.nav-button:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 25px rgba(79, 172, 254, 0.4);
  color: white;
}

.page-header {
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  color: white;
  padding: 2.5rem 2rem;
  border-radius: 16px;
  margin-bottom: 2rem;
  box-shadow: 0 10px 40px rgba(79, 172, 254, 0.3);
}

.page-header h1 {
  margin: 0;
  font-size: 2.5rem;
  font-weight: 700;
  text-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.content-section {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  margin: 2rem 0;
  box-shadow: 0 2px 8px rgba(0,0,0,0.05);
  border-left: 4px solid #4facfe;
}

.content-section h2 {
  color: #1a202c;
  margin-top: 0;
  font-weight: 700;
}

.content-section h3 {
  color: #2d3748;
  font-weight: 600;
}

.content-section p, .content-section ul {
  color: #2d3748;
  line-height: 1.8;
}

.team-highlight {
  background: linear-gradient(135deg, rgba(72, 187, 120, 0.1) 0%, rgba(104, 211, 145, 0.1) 100%);
  border-left: 5px solid #48bb78;
  padding: 1.75rem;
  border-radius: 10px;
  margin: 2rem 0;
}

.team-highlight strong {
  color: #1a202c;
  font-size: 1.1rem;
}

.team-highlight ul {
  margin: 1rem 0 0 0;
  color: #2d3748;
  line-height: 1.8;
}

.language-comparison {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  margin: 2rem 0;
}

.lang-card {
  background: white;
  border: 2px solid #e2e8f0;
  border-radius: 12px;
  padding: 1.75rem;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
}

.lang-card h3 {
  color: #4facfe;
  margin-top: 0;
  font-weight: 700;
}

.lang-card p, .lang-card ul {
  color: #2d3748;
  line-height: 1.7;
}

.lang-card strong {
  color: #1a202c;
}

pre {
  background: #1a202c;
  padding: 1.5rem;
  border-radius: 10px;
  overflow-x: auto;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

code {
  color: #e2e8f0;
  font-family: 'Courier New', monospace;
}

@media (max-width: 768px) {
  .nav-buttons, .language-comparison {
    flex-direction: column;
    grid-template-columns: 1fr;
  }
  
  .page-header h1 {
    font-size: 2rem;
  }
}
</style>

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/sprint1" class="nav-button">← Previous: Sprint 1</a>
  <a href="{{ site.baseurl }}/finalreviewblog/sprint3" class="nav-button">Next: Sprint 3 →</a>
</div>

<div class="page-header">
  <h1>Sprint 2: Python, JavaScript, and Teamwork</h1>
</div>

## A Fresh Start with a New Team

When we switched teams for Sprint 2, things felt different. My new group was organized and everyone had a clear role. It made me see that teamwork and communication are just as important as coding skills. Even if someone is good at programming, it doesn’t help the team if no one is on the same page.

<div class="team-highlight">
<strong>What Worked Well in This Team:</strong>
<ul>
  <li>Clear role assignments so everyone knew what to do</li>
  <li>Regular check-ins to make sure tasks were on track</li>
  <li>Shared notes about what each person was working on</li>
  <li>Helping each other instead of just doing someone else's work</li>
  <li>Being able to say "I don’t understand this" without feeling awkward</li>
</ul>
</div>

---

## Learning the Fundamentals

This sprint focused on the basics of Python and JavaScript. Python was mostly review for me, but JavaScript was new. Comparing the two languages helped me understand when to use each and how they handle similar concepts differently.

<div class="language-comparison">
  <div class="lang-card">
    <h3>Python</h3>
    <p><strong>What I Reviewed:</strong></p>
    <ul>
      <li>Lists, dictionaries, and sets</li>
      <li>Loops and conditionals</li>
      <li>Functions and parameters</li>
      <li>List comprehensions</li>
      <li>Basic object-oriented programming</li>
    </ul>
    <p><strong>Good For:</strong> Backend logic, data handling, clear syntax</p>
  </div>

  <div class="lang-card">
    <h3>JavaScript</h3>
    <p><strong>What I Learned:</strong></p>
    <ul>
      <li>Variable scoping (let, const, var)</li>
      <li>Arrow functions and callbacks</li>
      <li>Array methods like map, filter, and reduce</li>
      <li>DOM manipulation and event handling</li>
      <li>Making interactive pages</li>
    </ul>
    <p><strong>Good For:</strong> Frontend interactivity and user interfaces</p>
  </div>
</div>

---

## Teaching Conditionals and Game Work

I helped teach a lesson on conditionals in JavaScript, which made the topic clearer for me. We covered if/else statements, logical operators, ternary operators, and switch statements. Teaching the lesson forced me to notice details I might have missed, like operator precedence.

I also worked on the game section of the project, contributing to a block puzzle game called **Block Unlock**. The game used conditionals for game logic, like checking if blocks were in the correct place or if a player could make a move. Linking the game to the lesson on conditionals helped me see how programming concepts actually get applied in real projects.

---

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/sprint1" class="nav-button">← Previous: Sprint 1</a>
  <a href="{{ site.baseurl }}/finalreviewblog/sprint3" class="nav-button">Next: Sprint 3 →</a>
</div>

