---
layout: base
title: Sprint 2 - Fundamentals
description: Learning Python, JavaScript fundamentals, and the importance of teamwork
permalink: /finalreview/sprint2
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

.team-highlight {
  background: #f0fff4;
  border-left: 4px solid #48bb78;
  padding: 1.5rem;
  border-radius: 8px;
  margin: 2rem 0;
}

.language-comparison {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  margin: 2rem 0;
}

.lang-card {
  background: white;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 6px rgba(0,0,0,0.05);
}

@media (max-width: 768px) {
  .nav-buttons, .language-comparison {
    flex-direction: column;
    grid-template-columns: 1fr;
  }
}
</style>

<div class="nav-buttons">
  <a href="/finalreview/sprint1" class="nav-button">← Previous: Sprint 1</a>
  <a href="/finalreview/sprint3" class="nav-button">Next: Sprint 3 →</a>
</div>

# Sprint 2: Python, JavaScript, and Teamwork

## A Fresh Start with a New Team

When we switched to the second sprint and formed new groups, things started to change for me. My new team was really organized and made sure everyone had a clear role. It made me realize how important teamwork and communication are, and that being good at coding doesn't matter much if the group can't work together.

<div class="team-highlight">
<strong>What Made This Team Different:</strong>
<ul>
  <li><strong>Clear role assignments:</strong> Everyone knew what they were responsible for</li>
  <li><strong>Regular check-ins:</strong> We met before and after class to sync up</li>
  <li><strong>Shared documentation:</strong> We kept notes on what everyone was working on</li>
  <li><strong>No one left behind:</strong> If someone was stuck, we helped them instead of just doing it ourselves</li>
  <li><strong>Honest communication:</strong> We could say "I don't understand this" without feeling judged</li>
</ul>
</div>

---

## Diving into Fundamentals

This sprint focused on fundamentals, especially Python and JavaScript. I already knew a bit of Python from some online courses, so that was mostly review, but JavaScript was newer territory for me. What I found interesting was comparing the two languages and understanding when to use each one.

<div class="language-comparison">
  <div class="lang-card">
    <h3>Python</h3>
    <p><strong>What I Reviewed:</strong></p>
    <ul>
      <li>Data structures (lists, dictionaries, sets)</li>
      <li>Loops and conditionals</li>
      <li>Functions and parameters</li>
      <li>List comprehensions</li>
      <li>Object-oriented basics</li>
    </ul>
    <p><strong>Where It Shined:</strong> Backend logic, data processing, clean syntax for complex algorithms</p>
  </div>

  <div class="lang-card">
    <h3>JavaScript</h3>
    <p><strong>What I Learned:</strong></p>
    <ul>
      <li>Variable scoping (let, const, var)</li>
      <li>Arrow functions and callbacks</li>
      <li>Array methods (map, filter, reduce)</li>
      <li>DOM manipulation</li>
      <li>Event listeners and handlers</li>
    </ul>
    <p><strong>Where It Shined:</strong> Frontend interactivity, dynamic web content, user interface logic</p>
  </div>
</div>

---

## Teaching Conditionals

I actually ended up enjoying JavaScript a lot because it felt more dynamic and interactive. I also got to help teach a lesson on conditionals, which really helped me understand the topic better.

**What I Covered in My Lesson:**
- Basic if/else statements in both Python and JavaScript
- Comparison operators and logical operators (&&, ||, !)
- Ternary operators for concise conditionals
- Switch statements in JavaScript
- Practical examples: form validation, user authentication logic

**Why Teaching Helped Me:**
Explaining something out loud makes you notice the small details you might miss otherwise. For example, I didn't realize how important operator precedence was until someone asked why `x && y || z` didn't work the way they expected. It forced me to really understand the "why" behind the syntax, not just the "how."

---

## Key Concepts That Clicked

### JavaScript Array Methods
One of the most useful things I learned was how to use array methods like `map`, `filter`, and `reduce`. Instead of writing long for-loops, I could write cleaner, more readable code:

```javascript
// Old way I would have done it
let numbers = [1, 2, 3, 4, 5];
let doubled = [];
for (let i = 0; i < numbers.length; i++) {
    doubled.push(numbers[i] * 2);
}

// New way using map
let doubled = numbers.map(num => num * 2);
```

### Understanding Scope
Learning the difference between `var`, `let`, and `const` helped me avoid bugs. I learned that:
- `const` should be the default (prevents reassignment)
- `let` for variables that need to change
- `var` is outdated and causes weird scoping issues

---

## Challenges and Solutions

### Challenge: Homework Misalignment
The only issue I had during this sprint was that sometimes the homework didn't line up perfectly with what was taught in class, which made it a bit confusing. For example, we'd learn about basic conditionals in class, but the homework would expect us to use more advanced concepts like nested ternary operators or complex boolean logic.

**How I Handled It:**
- Reached out to teammates who might have figured it out
- Looked at documentation and examples online
- Asked specific questions in class rather than just saying "I don't get it"
- Realized that struggling with slightly harder problems actually helped me learn faster

---

## Growth in Confidence

This was the sprint where I started feeling a lot more confident in my skills. I could:
- Debug my own code more effectively
- Understand error messages instead of just panicking
- Write functions that were reusable and well-organized
- Contribute meaningfully to team discussions about technical decisions

The combination of strong teamwork and solid fundamental knowledge made this one of my favorite sprints.

---

<div class="nav-buttons">
  <a href="/finalreview/sprint1" class="nav-button">← Previous: Sprint 1</a>
  <a href="/finalreview/sprint3" class="nav-button">Next: Sprint 3 →</a>
</div>
