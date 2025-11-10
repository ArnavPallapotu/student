---
layout: base
title: What's Next
description: Future plans for the project and my learning journey in computer science
permalink: /finalreviewblog/future/
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

.content-section p, .content-section ul, .content-section ol {
  color: #d0d0d0;
  line-height: 1.8;
}

/* Ensure section text is readable */
.future-section p,
.future-section ul,
.future-section ol {
  color: #d0d0d0;
  line-height: 1.8;
}

.idea-card p,
.idea-card ul {
  color: #d0d0d0;
  line-height: 1.8;
}

.learning-goal p,
.learning-goal ul {
  color: #d0d0d0;
  line-height: 1.8;
}

.learning-goal strong {
  color: #ffffff;
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
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">← Previous: Night at the Museum</a>
  <a href="{{ site.baseurl }}/finalreviewblog/" class="nav-button">Back to Overview →</a>
</div>

<div class="page-header">
  <h1>What's Next</h1>
</div>

## Vault Improvements

The vault works well for unlocking scrolls, but I’d like to make it a bit more engaging.  

<div class="future-section">
<div class="idea-card">
<strong>Better Feedback & Visuals</strong>
- Smooth animation for the vault opening (we wanted a physical vault to be opened originally)
- Particle or celebration effects when a scroll is unlocked  
- Optional sound effects  
</div>

<div class="idea-card">
<strong>Progress & Challenge</strong>
- Adding a progress bar for the quiz which additionally updates user on percentage of questions right so far
- Secret scrolls or bonus challenges for more engagement (like a challenge lesson that gives you a secret vault code)
</div>
</div>

---

## Learning Goals: AI & Machine Learning

Over the summer, I taught a small, theoretical course on AI and machine learning for a non-profit. That experience made me curious about actually applying these ideas to code. I realized that it’s one thing to understand concepts on paper, but another to see them work in practice.  

<div class="learning-goal">
<h3>Data Analysis & Machine Learning</h3>

**Why This Interests Me:**  
I want to take the theory I taught over the summer and apply it to real data and real projects. It’s exciting to see patterns, make predictions, and solve problems with code.  

**Specific Goals:**  
- Work with pandas and NumPy for data analysis in Python  
- Explore data visualization with matplotlib or seaborn  
- Build a simple machine learning model (classification or regression)  
- Experiment with real datasets, maybe from Kaggle  

**Why It Matters:**  
Data science and machine learning are everywhere. Understanding how it works helps me connect computer science to real-world problems, and it lets me go from theory to actual code I can run and test.
</div>

---

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">← Previous: Night at the Museum</a>
  <a href="{{ site.baseurl }}/finalreviewblog/" class="nav-button">Back to Overview →</a>
</div>
