---
layout: default
title: "Home"
---

<!-- ═══════════════════════════════════════════
     SIDEBAR — photo, bio, contacts, socials
════════════════════════════════════════════ -->
<aside class="sidebar">

  <!-- Profile photo: replace src with your actual image path -->
  <!-- <img class="sidebar-photo" src="/assets/img/profile.jpg" alt="Marianna Miola"> -->
  <div class="sidebar-photo-placeholder">&#128100;</div>

  <div class="sidebar-name">Marianna Miola</div>
  <div class="sidebar-role">Your Role · Institution</div>

  <div class="sidebar-divider"></div>

  <ul class="sidebar-contacts">
    <li>
      <!-- Email icon -->
      <svg class="sidebar-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8">
        <rect x="2" y="4" width="20" height="16" rx="2"/><path d="m2 7 10 7 10-7"/>
      </svg>
      <a href="mailto:yourname@example.com">yourname@example.com</a>
    </li>
    <li>
      <!-- Location icon -->
      <svg class="sidebar-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8">
        <path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7z"/><circle cx="12" cy="9" r="2.5"/>
      </svg>
      City, Country
    </li>
  </ul>

  <!-- Social links -->
  <div class="sidebar-socials">

    <!-- GitHub -->
    <a class="sidebar-social-link" href="https://github.com/mariannamiola" target="_blank" rel="noopener" title="GitHub">
      <svg viewBox="0 0 24 24" fill="currentColor">
        <path d="M12 2C6.48 2 2 6.48 2 12c0 4.42 2.87 8.17 6.84 9.49.5.09.68-.22.68-.48v-1.7c-2.78.6-3.37-1.34-3.37-1.34-.45-1.16-1.1-1.47-1.1-1.47-.9-.62.07-.6.07-.6 1 .07 1.52 1.02 1.52 1.02.89 1.52 2.34 1.08 2.91.83.09-.64.35-1.08.63-1.33-2.22-.25-4.56-1.11-4.56-4.95 0-1.09.39-1.99 1.03-2.69-.1-.26-.45-1.27.1-2.65 0 0 .84-.27 2.75 1.02A9.56 9.56 0 0 1 12 6.8c.85 0 1.71.11 2.5.33 1.91-1.29 2.75-1.02 2.75-1.02.55 1.38.2 2.39.1 2.65.64.7 1.03 1.6 1.03 2.69 0 3.85-2.34 4.7-4.57 4.94.36.31.68.92.68 1.86v2.76c0 .27.18.58.69.48A10.01 10.01 0 0 0 22 12c0-5.52-4.48-10-10-10z"/>
      </svg>
    </a>

    <!-- LinkedIn -->
    <a class="sidebar-social-link" href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener" title="LinkedIn">
      <svg viewBox="0 0 24 24" fill="currentColor">
        <path d="M20.45 20.45h-3.56v-5.57c0-1.33-.03-3.04-1.85-3.04-1.85 0-2.13 1.44-2.13 2.94v5.67H9.35V9h3.41v1.56h.05c.48-.9 1.64-1.85 3.37-1.85 3.6 0 4.27 2.37 4.27 5.45v6.29zM5.34 7.43a2.07 2.07 0 1 1 0-4.14 2.07 2.07 0 0 1 0 4.14zM3.56 20.45h3.56V9H3.56v11.45zM22.23 0H1.77C.79 0 0 .77 0 1.72v20.56C0 23.23.79 24 1.77 24h20.46c.98 0 1.77-.77 1.77-1.72V1.72C24 .77 23.21 0 22.23 0z"/>
      </svg>
    </a>

    <!-- Google Scholar (optional) -->
    <a class="sidebar-social-link" href="https://scholar.google.com/citations?user=YOURID" target="_blank" rel="noopener" title="Google Scholar">
      <svg viewBox="0 0 24 24" fill="currentColor">
        <path d="M12 .587 0 9.65h3.085v9.26C5.05 20.46 8.36 21.6 12 21.6s6.95-1.14 8.915-2.69v-9.26H24zm0 13.563a5.14 5.14 0 1 1 0-10.28 5.14 5.14 0 0 1 0 10.28z"/>
      </svg>
    </a>

    <!-- ORCID (optional) -->
    <a class="sidebar-social-link" href="https://orcid.org/0000-0000-0000-0000" target="_blank" rel="noopener" title="ORCID">
      <svg viewBox="0 0 24 24" fill="currentColor">
        <path d="M12 0C5.372 0 0 5.372 0 12s5.372 12 12 12 12-5.372 12-12S18.628 0 12 0zM7.2 4.8a1.2 1.2 0 1 1 0 2.4 1.2 1.2 0 0 1 0-2.4zm-.9 4.2h1.8v10.2H6.3V9zm4.2 0h4.8c4.56 0 6.54 2.7 6.54 5.1 0 2.7-2.4 5.1-6.54 5.1h-4.8V9zm1.8 1.8v6.6h2.76c2.52 0 4.44-1.38 4.44-3.3 0-1.74-1.62-3.3-4.44-3.3h-2.76z"/>
      </svg>
    </a>

  </div>

  <!-- In-page anchor nav (quick jump) -->
  <nav>
    <ul class="sidebar-nav">
      <li><a href="#profile">Profile</a></li>
      <li><a href="#work">Work Experience</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

</aside>


<!-- ═══════════════════════════════════════════
     MAIN CONTENT
════════════════════════════════════════════ -->
<div class="main-wrapper">

  <!-- Top page navigation -->
  <nav class="top-nav">
    <a href="/" class="active">Home</a>
    <a href="/research/">Research</a>
    <a href="/talks/">Talks</a>
    <a href="/resources/">Resources</a>
  </nav>


  <!-- ── Hero ── -->
  <div class="hero">
    <h1>Hi, I'm <a href="https://github.com/mariannamiola">Marianna Miola</a></h1>
    <p>Welcome to my personal page. Here you'll find my projects, research work, talks, and resources.</p>
    <a class="btn-primary" href="/assets/CV.pdf" download>Download CV (PDF)</a>
  </div>

  <hr>


  <!-- ── Profile ── -->
  <div class="section" id="profile">
    <div class="section-header">
      <h2 class="section-title">Profile</h2>
    </div>
    <p class="profile-text">
      A short professional summary: who you are, what you do, and your goals.
      Mention your professional title, years of experience, the main industries you've worked in,
      and the key skills that define your practice.
    </p>
  </div>

  <hr>


  <!-- ── Work Experience ── -->
  <div class="section" id="work">
    <div class="section-header">
      <h2 class="section-title">Work Experience</h2>
    </div>

    <ol class="timeline">
      <li class="timeline-item">
        <div class="meta">mm/yyyy – mm/yyyy</div>
        <h3>Company A — Role</h3>
        <ul>
          <li>Brief description of the role and key outcomes</li>
          <li>Technologies used: <code>Python</code>, <code>JavaScript</code>, <code>React</code></li>
          <li>Measurable result (e.g., improved X by Y%, led project Z)</li>
        </ul>
      </li>

      <li class="timeline-item">
        <div class="meta">mm/yyyy – mm/yyyy</div>
        <h3>Company B — Role</h3>
        <ul>
          <li>Key achievement 1</li>
          <li>Key achievement 2</li>
        </ul>
      </li>
    </ol>
  </div>

  <hr>


  <!-- ── Education ── -->
  <div class="section" id="education">
    <div class="section-header">
      <h2 class="section-title">Education</h2>
    </div>

    <div class="card">
      <div class="meta">University XYZ · yyyy–yyyy</div>
      <h3>Degree in [Program Name]</h3>
      <ul>
        <li>Capstone / Thesis: [Optional]</li>
      </ul>
    </div>

    <div class="card">
      <div class="meta">Issuing organization · yyyy</div>
      <h3>Certification ABC</h3>
    </div>
  </div>

  <hr>


  <!-- ── Skills ── -->
  <div class="section" id="skills">
    <div class="section-header">
      <h2 class="section-title">Skills</h2>
    </div>

    <div class="skills-grid">
      <div class="card">
        <div class="meta">Languages</div>
        <p>JavaScript, Python, TypeScript</p>
      </div>
      <div class="card">
        <div class="meta">Frameworks &amp; Libraries</div>
        <p>React, Vue, Node.js</p>
      </div>
      <div class="card">
        <div class="meta">Tools &amp; DevOps</div>
        <p>Git, GitHub Actions, Docker</p>
      </div>
      <div class="card">
        <div class="meta">Other</div>
        <p>UX/UI, Agile, Scrum</p>
      </div>
    </div>
  </div>

  <hr>


  <!-- ── Projects ── -->
  <div class="section" id="projects">
    <div class="section-header">
      <h2 class="section-title">Key Projects</h2>
    </div>

    <div class="card">
      <div class="meta">Main technologies used</div>
      <h3><a href="https://github.com/mariannamiola/progetto1">Project Name 1</a></h3>
      <p>Brief description of the project and your role.</p>
    </div>

    <div class="card">
      <h3><a href="https://github.com/mariannamiola/progetto2">Project Name 2</a></h3>
      <p>Short description and impact.</p>
    </div>
  </div>

  <hr>


  <!-- ── Contact ── -->
  <div class="section" id="contact">
    <div class="section-header">
      <h2 class="section-title">Contact</h2>
    </div>

    <div class="card">
      <ul>
        <li>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></li>
        <li>LinkedIn: <a href="https://linkedin.com/in/yourprofile">yourprofile</a></li>
        <li>GitHub: <a href="https://github.com/mariannamiola">mariannamiola</a></li>
      </ul>
    </div>
  </div>


  <div class="section-footer">I'll keep this page updated with new experience and projects.</div>

</div><!-- /.main-wrapper -->
