---
layout: base
title: Sprint 3 - Digital Famine Project
description: Building our final project with better organization and teamwork
permalink: /finalreviewblog/sprint3/
toc: true
comments: true
---

<style>
.nav-buttons {
  display: flex;
  justify-content: space-between;
  margin: 20px 0;
}
.nav-button {
  padding: 8px 16px;
  background: linear-gradient(90deg, #007bff, #00c6ff);
  color: white;
  text-decoration: none;
  border-radius: 10px;
  font-weight: 500;
  transition: 0.3s ease;
}
.nav-button:hover {
  opacity: 0.85;
  transform: scale(1.02);
}
.page-header {
  text-align: center;
  margin: 40px 0;
}
.content-section {
  background-color: #f8f9fa;
  border-radius: 15px;
  padding: 25px;
  margin-bottom: 20px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
}
.success-box, .reflection-box {
  background-color: #e8f6f3;
  border-left: 5px solid #00a884;
  padding: 20px;
  border-radius: 10px;
  margin-top: 20px;
}
.feature-showcase {
  background-color: #eef6ff;
  border-left: 5px solid #007bff;
  padding: 20px;
  border-radius: 10px;
  margin-top: 20px;
}
h2 {
  color: #333;
  margin-top: 0;
}
</style>

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">← Previous: Sprint 2</a>
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">Next: Night at the Museum →</a>
</div>

<div class="page-header">
  <h1>Sprint 3: Digital Famine Project</h1>
</div>

<div class="content-section">
  <h2>Reuniting with Original Team</h2>
  <p>In the final sprint, I went back to my original group for the Digital Famine project. This time, though, things were completely different. We had all grown as developers and as teammates. We were much more organized than before, everyone had a specific task, and we communicated better. It was like night and day compared to Sprint 1.</p>

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
</div>

<div class="content-section">
  <h2>The Digital Famine Concept</h2>
  <p>Our project was an educational game with a storyline where users learn about computer science concepts by completing lessons. As they progress, they unlock parts of the story and collect scrolls that reveal more about the "digital famine" narrative.</p>

  <p><strong>Core Features:</strong></p>
  <ul>
    <li>Interactive lessons on programming concepts</li>
    <li>Story-driven progression system</li>
    <li>Vault feature for unlocking rewards</li>
    <li>Quiz system to test knowledge</li>
    <li>Progress tracking and save system</li>
  </ul>
</div>

<div class="content-section">
  <h2>My Contributions</h2>

  <div class="feature-showcase">
    <h3>Vault System</h3>
    <p>I worked mainly on the Vault feature — after completing lessons, users would get a code they could enter into the vault to unlock a scroll as part of our storyline.</p>

    <p><strong>How It Worked:</strong></p>
    <ol>
      <li>Complete a lesson module</li>
      <li>Receive a unique unlock code</li>
      <li>Enter code in the Vault interface</li>
      <li>Unlock a scroll with story content and lore</li>
      <li>Track progress in user's profile</li>
    </ol>

    <p><strong>Technical Implementation:</strong></p>
    <ul>
      <li>Used localStorage to save unlocked scrolls</li>
      <li>Implemented code validation system</li>
      <li>Created animations for the unlock sequence</li>
      <li>Designed the visual interface for the vault</li>
      <li>Added error handling for invalid codes</li>
    </ul>

    <p><strong>Challenges I Faced:</strong></p>
    <ul>
      <li>Making sure codes couldn't be guessed easily</li>
      <li>Preventing users from unlocking scrolls out of order</li>
      <li>Creating smooth animations that didn't lag</li>
      <li>Syncing vault progress with overall game progress</li>
    </ul>
  </div>

  <h3>Vault Quiz System</h3>
  <p>I also helped with the Vault quiz, which tested everything the player had learned. The quiz had to be smart enough to:</p>
  <ul>
    <li>Pull questions from multiple topic areas</li>
    <li>Track which concepts the user struggled with</li>
    <li>Provide immediate feedback on answers</li>
    <li>Save quiz results for later review</li>
    <li>Generate different questions each time</li>
  </ul>

  <p><strong>What I Learned:</strong></p>
  <ul>
    <li>How to randomize arrays without repeating elements</li>
    <li>Creating reusable quiz components</li>
    <li>Better UI/UX for question displays</li>
    <li>Form validation and user feedback patterns</li>
  </ul>
</div>

<div class="reflection-box">
  <strong>If I Could Do It Over:</strong>
  <p>If I could change anything, I'd probably spend more time helping with the actual lesson content instead of just the coding side. I tested all the lessons and noticed some parts that could've been clearer, but we didn't have enough time to fix them before the deadline. Another problem was that our theming on the page was super inconsistent, with different colors and fonts. This didn’t represent our teamwork well, and it’s something I’d fix next time.</p>

  <p><strong>Specific Improvements:</strong></p>
  <ul>
    <li>More consistent difficulty progression in lessons</li>
    <li>Better explanations for complex concepts</li>
    <li>More interactive examples in each lesson</li>
    <li>Clearer instructions for users</li>
    <li>Better error messages when users get stuck</li>
  </ul>

  <p><strong>Time Management:</strong> We should have started lesson content earlier instead of focusing so heavily on vault and quiz systems first. The features were great, but they're useless if the lessons aren't engaging.</p>
</div>

<div class="content-section">
  <h2>Team Dynamics Success</h2>
  <p>Compared to Sprint 1, our teamwork was much better, though I sometimes had to assign tasks to myself instead of being given them directly.</p>

  <p><strong>Communication:</strong></p>
  <ul>
    <li>Group chat updates and discussions</li>
    <li>Collaborating during 4th period work sessions</li>
    <li>Honest feedback when something wasn’t working</li>
  </ul>

  <p><strong>Problem-Solving:</strong></p>
  <ol>
    <li>Worked through blockers as a team</li>
    <li>Messaged each other after school when needed</li>
    <li>Tracked mistakes to avoid repeating them</li>
  </ol>

  <p><strong>Code Quality Improvements:</strong></p>
  <ul>
    <li>Code reviews before pushing (after theming issues taught us a lesson)</li>
    <li>Consistent naming and permalink conventions</li>
  </ul>
</div>

<div class="content-section">
  <h2>Technical Growth</h2>
  <p>This sprint pushed me to learn:</p>
  <p><strong>Frontend:</strong></p>
  <ul>
    <li>Combining CSS and Markdown</li>
    <li>Responsive navigation design</li>
    <li>Clean layout organization</li>
  </ul>
  <p><strong>General:</strong></p>
  <ul>
    <li>Stronger teamwork and communication</li>
    <li>Debugging through collaboration</li>
    <li>Writing clearer documentation and comments</li>
  </ul>
</div>

<div class="content-section">
  <h2>Pride Points</h2>
  <ul>
    <li>The vault’s functionality and design</li>
    <li>Save feature on the quiz</li>
    <li>Team collaboration and completion</li>
    <li>Finishing a fully working project</li>
  </ul>
</div>

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/sprint2" class="nav-button">← Previous: Sprint 2</a>
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">Next: Night at the Museum →</a>
</div>
