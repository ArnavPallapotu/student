---
layout: base
title: Sprint 3 - Digital Famine Project
description: Building our final project with better organization and teamwork
permalink: /finalreviewblog/sprint3/
toc: true
comments: true
---

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">← Previous: Sprint 2</a>
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">Next: Night at the Museum →</a>
</div>

<div class="page-header">
  <h1>Sprint 3: Digital Famine Project</h1>
</div>

## Reuniting with Original Team

In the final sprint, I went back to my original group for the Digital Famine project. This time, though, things were completely different. We had all grown as developers and as teammates. We were much more organized than before, everyone had a specific task, and we communicated better. It was like night and day compared to Sprint 1.

<div class="success-box">
<strong>What Improved from Sprint 1:</strong>
<ul>
  <li><strong>Better planning:</strong> We mapped out features before coding</li>
  <li><strong>Clear task distribution:</strong> Everyone owned specific features</li>
  <li><strong>Version control discipline:</strong> Proper branching and pull requests</li>
  <li><strong>Regular testing:</strong> We tested each feature as it was built</li>
  <li><strong>Honest timelines:</strong> We didn't over-promise what we could deliver</li>
</ul>
</div>

---

## The Digital Famine Concept

Our project was an educational game with a storyline where users learn about computer science concepts by completing lessons. As they progress, they unlock parts of the story and collect scrolls that reveal more about the "digital famine" narrative.

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
5. Track progress in user's profile  

**Technical Implementation:**  
- Used localStorage to save unlocked scrolls  
- Implemented code validation system  
- Created animations for the unlock sequence  
- Designed the visual interface for the vault  
- Added error handling for invalid codes  

**Challenges I Faced:**  
- Making sure codes couldn't be guessed easily  
- Preventing users from unlocking scrolls out of order  
- Creating smooth animations that didn't lag  
- Syncing vault progress with overall game progress  
</div>

### Vault Quiz System

I also helped with the Vault quiz, which tested everything the player had learned. The quiz had to be smart enough to:
- Pull questions from multiple topic areas  
- Track which concepts the user struggled with  
- Provide immediate feedback on answers  
- Save quiz results for later review  
- Generate different questions each time  

**What I Learned:**  
- How to randomize arrays without repeating elements  
- Creating reusable quiz components  
- Better UI/UX for question displays  
- Form validation and user feedback patterns  

---

## What I'd Change

<div class="reflection-box">
<strong>If I Could Do It Over:</strong>

If I could change anything, I'd probably spend more time helping with the actual lesson content instead of just the coding side. I tested all the lessons and noticed some parts that could've been clearer, but we didn't have enough time to fix them before the deadline. Another problem was that our themeing on the page was super inconsistent, with different colors and different fonts on everything. This was not a good representation of our teamwork, and this should be considered next time.

**Specific Improvements:**  
- More consistent difficulty progression in lessons  
- Better explanations for complex concepts  
- More interactive examples in each lesson  
- Clearer instructions for what users need to do  
- Better error messages when users get stuck  

**Time Management:**  
We should have started the lesson content earlier instead of focusing so heavily on the vault and quiz systems first. The features were great, but they're useless if the lessons aren't engaging.
</div>

---

## Team Dynamics Success

Compared to Sprint 1, our teamwork was much better in comparison; however, I somehow felt like I had to assign my own work to myself rather than being given tasks to do.

**Communication:**  
- Messages to each other in our group chat  
- Worked together as a team every 4th period  
- Updated each other on progress  
- Gave honest feedback when something wasn’t working  

**Problem-Solving:**  
When someone hit a roadblock, we’d:  
1. Work through it together as a team  
2. Message each other at home  
3. Make sure we didn’t repeat mistakes  

**Code Quality Improvements:**  
- Code reviews before pushing (we caught themeing issues this way)  
- Consistent naming conventions (especially after permalink changes)  

---

## Technical Growth

This sprint pushed me to learn:  

**Frontend:**  
- CSS and markdown in combination  
- Making sure navigation works on every page  
- Keeping the site responsive and visually clean  

**General:**  
- Better teamwork in a group setting  
- How to handle errors and debug efficiently  
- The importance of documentation and commenting code  

---

## Pride Points

Despite the things I'd change, I was proud of:  
- The functionality and intuitiveness of the vault  
- Save feature on the quiz  
- How well our team collaborated  
- Finishing a complete, working project  

---

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">← Previous: Sprint 2</a>
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">Next: Night at the Museum →</a>
</div>
