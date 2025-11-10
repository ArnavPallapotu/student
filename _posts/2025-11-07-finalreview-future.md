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

/* Match sprint page structure */
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
.content-section h2, .content-section h3 {
  color: #ffffff;
}

/* Ensure existing boxes inherit readable text */
.content-section p, .content-section ul, .content-section ol,
.future-section p, .future-section ul, .future-section ol,
.idea-card p, .idea-card ul,
.learning-goal p, .learning-goal ul {
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

<!-- Replace the markdown H1 with a page header -->
<div class="page-header">
  <h1>What's Next</h1>
</div>

<!-- Wrap each section in content-section for consistent layout -->
<div class="content-section">
  <h2>Project Improvements</h2>
  <h3>Vault Improvements</h3>
  <p>The vault works well for unlocking scrolls, but I'd like to make it more engaging.</p>
  <div class="future-section">
    <div class="idea-card">
      <strong>Better Feedback & Visuals</strong>
      <ul>
        <li>Smooth animation for the vault opening (original goal was a physical vault effect)</li>
        <li>Celebration / particle effect when a scroll unlocks</li>
        <li>Optional sound effects toggle</li>
      </ul>
    </div>
    <div class="idea-card">
      <strong>Progress & Challenge</strong>
      <ul>
        <li>Progress bar for quiz + live correct percentage</li>
        <li>Secret scrolls / bonus challenge lesson that grants a hidden code</li>
      </ul>
    </div>
  </div>
</div>

<div class="content-section">
  <h2>Lesson Content Improvements</h2>
  <h3>Focus Areas</h3>
  <ul>
    <li>Smoother difficulty ramp across lessons</li>
    <li>Clearer explanations for harder concepts</li>
    <li>More interactive examples (inline code playgrounds)</li>
    <li>Consistent theme (fonts, spacing, color use)</li>
  </ul>
</div>

<div class="content-section">
  <h2>Learning Goals: AI & Machine Learning</h2>
  <h3>Data Analysis & Machine Learning</h3>
  <p><strong>Why This Interests Me:</strong> I taught a small theoretical AI course over the summer and now want to actually build things—moving from ideas to code I can run.</p>
  <p><strong>Specific Goals:</strong></p>
  <ul>
    <li>Use pandas & NumPy for real data analysis</li>
    <li>Create visualizations with matplotlib or seaborn</li>
    <li>Build a simple ML model (classification or regression)</li>
    <li>Experiment with real datasets (possibly Kaggle)</li>
  </ul>
  <p><strong>Why It Matters:</strong> ML connects CS to real problems—pattern recognition, prediction, and insight. It lets me turn theory into testable code.</p>
</div>

<div class="content-section">
  <h2>Near-Term Projects</h2>
  <h3>Summer Project Ideas</h3>
  <ul>
    <li><strong>Interactive AI Chatbot:</strong> Explains its reasoning while answering.</li>
    <li><strong>Data Visualizer:</strong> Upload data → auto charts + summary.</li>
    <li><strong>Model Explorer:</strong> Tweak parameters, see decision boundary changes live.</li>
    <li><strong>AI Ethics Debate Space:</strong> Guided prompts + moderated threads.</li>
  </ul>
</div>

<div class="content-section">
  <h2>Long-Term Vision</h2>
  <h3>Impact Areas</h3>
  <ul>
    <li>AI for accessibility tools</li>
    <li>Energy / sustainability optimization</li>
    <li>Personalized education platforms</li>
  </ul>
  <p>I want to build things that are useful and thoughtful, not just technically impressive.</p>
</div>

<div class="content-section">
  <h2>How I'll Get There</h2>
  <h3>Structured Approach</h3>
  <ul>
    <li>Targeted courses (data, ML, ethics)</li>
    <li>Small iterative personal projects</li>
    <li>Open source contributions for real-world patterns</li>
    <li>Community (forums, hackathons, discussions)</li>
  </ul>
  <h3>Habits</h3>
  <ul>
    <li>Document lessons learned after each project</li>
    <li>Refactor old code with new techniques</li>
    <li>Balance depth vs breadth—finish things</li>
  </ul>
</div>

<div class="nav-buttons">
  <a href="{{ site.baseurl }}/finalreviewblog/natm" class="nav-button">← Previous: Night at the Museum</a>
  <a href="{{ site.baseurl }}/finalreviewblog/" class="nav-button">Back to Overview →</a>
</div>
