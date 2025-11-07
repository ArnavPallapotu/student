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

.team-highlight {
  background: #2a2a2a;
  border-left: 5px solid #48bb78;
  padding: 1.75rem;
  border-radius: 10px;
  margin: 2rem 0;
  border: 1px solid #333;
}

.team-highlight strong {
  color: #ffffff;
  font-size: 1.1rem;
}

.team-highlight ul {
  margin: 1rem 0 0 0;
  color: #d0d0d0;
  line-height: 1.8;
}

.language-comparison {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  margin: 2rem 0;
}

.lang-card {
  background: #1a1a1a;
  border: 2px solid #333;
  border-radius: 12px;
  padding: 1.75rem;
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}

.lang-card h3 {
  color: #4facfe;
  margin-top: 0;
  font-weight: 700;
}

.lang-card p, .lang-card ul {
  color: #d0d0d0;
  line-height: 1.7;
}

.lang-card strong {
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

