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

.feature-showcase {
  background: linear-gradient(135deg, rgba(79, 172, 254, 0.1) 0%, rgba(0, 242, 254, 0.1) 100%);
  border-radius: 12px;
  padding: 2rem;
  margin: 2rem 0;
  border: 2px solid #e2e8f0;
}

.feature-showcase h3 {
  color: #4facfe;
  margin-top: 0;
  font-weight: 700;
}

.reflection-box {
  background: linear-gradient(135deg, rgba(252, 129, 129, 0.1) 0%, rgba(254, 178, 178, 0.1) 100%);
  border-left: 5px solid #fc8181;
  padding: 1.75rem;
  border-radius: 10px;
  margin: 2rem 0;
}

.reflection-box strong {
  color: #1a202c;
  font-size: 1.1rem;
}

.success-box {
  background: linear-gradient(135deg, rgba(72, 187, 120, 0.1) 0%, rgba(104, 211, 145, 0.1) 100%);
  border-left: 5px solid #48bb78;
  padding: 1.75rem;
  border-radius: 10px;
  margin: 2rem 0;
}

.success-box strong {
  color: #1a202c;
  font-size: 1.1rem;
}

.success-box ul, .reflection-box ul {
  margin: 1rem 0 0 0;
  color: #2d3748;
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

If I could change anything, I'd probably spend more time helping with the actual lesson content instead of just the coding side. I tested all the lessons and noticed some parts that could've been clearer, but we didn't have enough time to fix them before the deadline.

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

What made this sprint successful was how well we worked together:

**Communication:**
- Daily standup messages in our group chat
- Weekly video calls to check major progress
- Shared Google Doc for tracking who's doing what
- Honest feedback when something wasn't working

**Problem-Solving:**
When someone hit a roadblock, we'd:
1. Try to solve it individually for ~30 minutes
2. Ask the group chat for hints
3. Screen-share if it's still not working
4. Document the solution so others don't hit the same issue

**Code Quality:**
- Code reviews before merging
- Consistent naming conventions
- Comments on complex logic
- README documentation for setup

---

## Technical Growth

This sprint pushed me to learn:

**Frontend:**
- More advanced CSS animations
- Better component organization
- Responsive design principles
- Accessibility considerations

**Backend:**
- Data persistence strategies
- User authentication concepts (even though we simplified it)
- API design thinking
- Error handling best practices

**General:**
- Project architecture planning
- Feature prioritization
- MVP (Minimum Viable Product) thinking
- Balancing perfectionism with deadlines

---

## Pride Points

Despite the things I'd change, I was genuinely proud of:
- The smooth unlock animations in the vault
- How we handled edge cases (like duplicate codes)
- The quiz feedback system
- How well our team collaborated
- Actually finishing a complete, working project

---

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">← Previous: Sprint 2</a>
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">Next: Night at the Museum →</a>
</div>
