---
layout: base
title: Sprint 3 - Digital Famine Project
description: Building our final project with better organization and teamwork
permalink: /finalreviewblog/sprint3/
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

.feature-showcase {
  background: #2a2a2a;
  border-radius: 12px;
  padding: 2rem;
  margin: 2rem 0;
  border: 2px solid #333;
}

.feature-showcase h3 {
  color: #4facfe;
  margin-top: 0;
  font-weight: 700;
}

.reflection-box {
  background: #2a2a2a;
  border-left: 5px solid #fc8181;
  padding: 1.75rem;
  border-radius: 10px;
  margin: 2rem 0;
  border: 1px solid #333;
}

.reflection-box strong {
  color: #ffffff;
  font-size: 1.1rem;
}

.success-box {
  background: #2a2a2a;
  border-left: 5px solid #48bb78;
  padding: 1.75rem;
  border-radius: 10px;
  margin: 2rem 0;
  border: 1px solid #333;
}

.success-box strong {
  color: #ffffff;
  font-size: 1.1rem;
}

.success-box ul, .reflection-box ul {
  margin: 1rem 0 0 0;
  color: #d0d0d0;
  line-height: 1.8;
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
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">← Previous: Sprint 2</a>
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">Next: Night at the Museum →</a>
</div>

<div class="page-header">
  <h1>Sprint 3: Digital Famine Project</h1>
</div>

## Reuniting with Original Team

In the final sprint, I went back to my original group for the Digital Famine project. This time, things were completely different. We had all grown as developers and teammates. We were much more organized, everyone had a specific task, and we communicated better. It was like night and day compared to Sprint 1.

<div class="success-box">
<strong>What Improved from Sprint 1:</strong>
<ul>
  <li><strong>Better planning:</strong> We mapped out features before coding</li>
  <li><strong>Clear task distribution:</strong> Everyone owned specific features</li>
  <li><strong>Version control discipline:</strong> Proper branching and pull requests</li>
  <li><strong>Regular testing:</strong> We tested each feature as it was built</li>
  <li><strong>Honest timelines:</strong> We didn’t over-promise what we could deliver</li>
</ul>
</div>

---

## The Digital Famine Concept

Our project was an educational game where users learned computer science concepts through lessons. As they progressed, they unlocked parts of the story and collected scrolls that revealed more about the “digital famine” world.

**Core Features:**
- Interactive lessons on programming concepts  
- Story-driven progression system  
- Vault feature for unlocking rewards  
- Quiz system to test knowledge  
- Progress tracking and save system  

---

## My Contributions

### The Vault Feature

<div class="feature-showcase">
<h3>Vault System</h3>

I worked mainly on the Vault feature — after completing lessons, users would get a code they could enter into the vault to unlock a scroll as part of our storyline.

**How It Worked:**
1. Complete a lesson module  
2. Receive a unique unlock code  
3. Enter code in the Vault interface  
4. Unlock a scroll with story content and lore  
5. Track progress in the user’s profile  

**Technical Implementation:**
- Used localStorage to save unlocked scrolls  
- Implemented code validation system  
- Created animations for the unlock sequence  
- Designed the visual interface for the vault  
- Added error handling for invalid codes  

**Challenges I Faced:**
- Making sure codes couldn’t be guessed easily  
- Preventing users from unlocking scrolls out of order  
- Creating smooth animations without lag  
- Syncing vault progress with overall game progress  
</div>

### Vault Quiz System

I also helped with the Vault quiz, which tested everything the player had learned. The quiz had to:
- Pull questions from multiple topic areas  
- Track which concepts the user struggled with  
- Provide immediate feedback  
- Save quiz results for review  
- Generate different questions each time  

**What I Learned:**
- How to randomize arrays without repeats  
- Creating reusable quiz components  
- UI/UX for question displays  
- Form validation and feedback  

---

## What I'd Change

<div class="reflection-box">
<strong>If I Could Do It Over:</strong>

If I could change anything, I’d spend more time improving the lesson content instead of focusing only on the vault and quiz. I noticed some lessons could have been clearer, but we didn’t have enough time to fix them before the deadline. Our theming also got inconsistent — fonts and colors didn’t always match — which made the project feel slightly unfinished.

**Specific Improvements:**
- More consistent lesson difficulty  
- Clearer explanations for complex concepts  
- More interactive examples  
- Better instructions and error messages  

**Time Management:**
We should have started lesson content earlier instead of focusing so heavily on vault and quiz systems. The features were great, but they depend on strong lesson design.
</div>

---

## Team Dynamics Success

Compared to Sprint 1, our teamwork was much better, though I sometimes had to assign myself tasks instead of being given them.

**Communication:**
- Group chat messages and in-class updates  
- Regular check-ins every 4th period  
- Honest feedback when something didn’t work  

**Problem-Solving:**
When someone hit a roadblock, we would:  
1. Work through it together  
2. Message at home  
3. Make sure we didn’t repeat mistakes  

**Code Quality Improvements:**
- Code reviews before pushing (our theme broke once because we didn’t)  
- Consistent naming conventions (permalink confusion was real)  

---

## Technical Growth

This sprint pushed me to learn:

**Frontend:**
- CSS and markdown integration  
- Responsive design and clean navigation  

**General:**
- Working efficiently in teams  
- Handling bugs and errors together  
- Writing clearer code and documentation  

---

## Pride Points

Despite what I’d change, I was proud of:
- The vault’s functionality and animations  
- The quiz save system  
- How well our team collaborated  
- Actually finishing a polished project  

---

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">← Previous: Sprint 2</a>
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">Next: Night at the Museum →</a>
</div>
