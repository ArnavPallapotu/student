---
layout: base
title: Sprint 1 - Tools and APIs
description: My first sprint learning development tools and working with APIs
permalink: /finalreview/sprint1
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

.highlight-box {
  background: linear-gradient(135deg, #667eea15 0%, #764ba215 100%);
  border-left: 4px solid #667eea;
  padding: 1.5rem;
  border-radius: 8px;
  margin: 2rem 0;
}

.project-showcase {
  background: white;
  border: 1px solid #e2e8f0;
  border-radius: 12px;
  padding: 2rem;
  margin: 2rem 0;
  box-shadow: 0 4px 6px rgba(0,0,0,0.05);
}

.project-showcase h3 {
  color: #667eea;
  margin-top: 0;
}

@media (max-width: 768px) {
  .nav-buttons {
    flex-direction: column;
  }
}
</style>

<div class="nav-buttons">
  <a href="/finalreview/comparison" class="nav-button">← Previous: Then vs Now</a>
  <a href="/finalreview/sprint2" class="nav-button">Next: Sprint 2 →</a>
</div>

# Sprint 1: Tools and APIs

## The Struggle of Getting Started

At the beginning of the year, I struggled a lot with the setup process and just figuring out what to do. My group at the time was really advanced, and while they worked quickly, I often felt left behind. They didn't really explain what I should be doing, so I had to figure out a lot of things on my own. The worst part was getting my tools to actually work — I kept running into issues with make commands and virtual environments that I didn't know how to fix. Everyone else seemed to have their environment running smoothly while I was stuck troubleshooting for hours.

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

## Finding My Role

Still, I tried to contribute however I could, and once we started working on actual projects, I actually enjoyed it a lot. Even though the setup was frustrating, the coding part was fun.

---

## Working with APIs

One of my first contributions was helping make a lesson on APIs for the class hacks (basically mini lessons we teach each other). I specifically worked on the part about asynchronous functions and the `await` keyword. It was helpful because teaching something forces you to actually understand it.

After that, I worked on an iTunes API project where we took an existing hack and added our own features to it. We added things like:
- A search bar that saves your results so you don't lose them
- A feature where you can filter songs by different genres
- Some other small improvements to make it more user-friendly

It wasn't anything crazy, but it was one of the first times I felt like I actually built something that worked and did something useful.

---

## Understanding Asynchronous Code

This was probably the most important thing I learned in Sprint 1. At first, I didn't get why we couldn't just grab data from an API immediately. But once I understood how asynchronous JavaScript works, it made way more sense:

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

Understanding this pattern changed how I thought about coding. It wasn't just about copying examples — it was about actually knowing why things work the way they do.

---

## Lessons Learned

### Technical Skills
- How to work with APIs and handle asynchronous code
- Basic understanding of `async`, `await`, and promises
- Using `fetch()` to get data from external sources
- Debugging when things don't work (which was often)

### Soft Skills
- **Persistence:** Not giving up even when setup was frustrating
- **Figuring things out independently:** Had to google a lot when teammates couldn't help
- **Asking questions:** Learned it's better to ask than stay confused
- **Teaching others:** Explaining async concepts helped me understand them better

---

## What I'd Do Differently

Looking back, I wish I had:
- Asked for help earlier with the virtual environment issues instead of wasting time
- Been more assertive about what I should be working on
- Taken better notes on the setup process so I wouldn't forget
- Spent more time understanding Git from the beginning

Despite the rough start, this sprint taught me a lot — mostly that struggling through problems is part of learning, and that it's okay to not understand everything immediately.

---

<div class="nav-buttons">
  <a href="/finalreview/comparison" class="nav-button">← Previous: Then vs Now</a>
  <a href="/finalreview/sprint2" class="nav-button">Next: Sprint 2 →</a>
</div>
