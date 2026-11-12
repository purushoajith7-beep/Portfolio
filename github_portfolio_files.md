# Malakiadas Purushothaman — GitHub Portfolio Files

To publish your portfolio on GitHub Pages, create a new repository on GitHub (for example, `malakiadas-portfolio`) and upload the following files into the main root folder:

- `index.html`
- `style.css`
- `script.js`
- `README.md`
- `profile.jpg` *(your uploaded photo, renamed to `profile.jpg`)*

---

## 1. `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Malakiadas Purushothaman | International Marketing Portfolio</title>
  <link rel="stylesheet" href="style.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">
</head>
<body>

  <!-- Navigation -->
  <header class="navbar">
    <div class="container nav-container">
      <a href="#home" class="logo">M. Purushothaman<span>.</span></a>
      <nav class="nav-links" id="navLinks">
        <a href="#about">About</a>
        <a href="#skills">Expertise</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Marketing Cases</a>
        <a href="#education">Education</a>
        <a href="#contact" class="btn-nav">Contact</a>
      </nav>
      <button class="hamburger" id="hamburger" aria-label="Toggle Menu">
        <span></span>
        <span></span>
        <span></span>
      </button>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="container hero-grid">
      <div class="hero-content">
        <span class="badge">Available for International Marketing Roles • Paris, France</span>
        <h1>Malakiadas <br><span>Purushothaman</span></h1>
        <h2>Master’s Student in International Marketing &amp; Digital Media Strategist</h2>
        <p>
          Bridging cross-cultural brand strategy, digital storytelling, and commercial execution across 
          <strong>France, the UK, and India</strong>. Combining creative production mastery with data-driven global market insights.
        </p>
        <div class="hero-buttons">
          <a href="#projects" class="btn btn-primary">Explore Marketing Work</a>
          <a href="#contact" class="btn btn-outline">Get in Touch</a>
        </div>
        <div class="hero-stats">
          <div>
            <strong>3</strong>
            <span>Global Markets (FR, UK, IN)</span>
          </div>
          <div>
            <strong>2</strong>
            <span>Master’s Degrees</span>
          </div>
          <div>
            <strong>3</strong>
            <span>Languages Spoken</span>
          </div>
        </div>
      </div>
      <div class="hero-visual">
        <div class="profile-card">
          <!-- Make sure your photo file in GitHub is named profile.jpg -->
          <img src="profile.jpg" alt="Malakiadas Purushothaman" onerror="this.src='https://ui-avatars.com/api/?name=Malakiadas+Purushothaman&size=400&background=1e293b&color=d97706&bold=true'">
          <div class="profile-tag">
            <span>ESCE Business School</span>
            <small>Paris • International Marketing</small>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="section bg-light">
    <div class="container">
      <div class="section-header">
        <span class="subtitle">Profile</span>
        <h3>Global Mindset. Creative Execution.</h3>
      </div>
      <div class="about-grid">
        <div class="about-text">
          <p>
            Currently pursuing a <strong>Master’s in International Marketing</strong> at <strong>ESCE Business School in Paris</strong>, I bring a rare combination of formal marketing strategy and hands-on digital media production.
          </p>
          <p>
            Having lived, studied, and worked across <strong>India, the United Kingdom, and France</strong>, I understand how brands adapt their messaging to resonate across diverse cultural landscapes. My background includes a Master’s in Digital Media from London Metropolitan University, team leadership in fast-paced London hospitality operations, and commercial graphic design.
          </p>
        </div>
        <div class="about-highlights">
          <div class="highlight-box">
            <h4>Languages</h4>
            <ul>
              <li><strong>English:</strong> Fluent / Bilingual</li>
              <li><strong>French:</strong> Intermediate (DELF Certified)</li>
              <li><strong>Tamil:</strong> Native</li>
            </ul>
          </div>
          <div class="highlight-box">
            <h4>Core Strengths</h4>
            <ul>
              <li>Cross-Cultural Brand Positioning</li>
              <li>Visual Content &amp; Campaign Production</li>
              <li>Customer Experience &amp; Team Leadership</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills & Tools Section -->
  <section id="skills" class="section">
    <div class="container">
      <div class="section-header">
        <span class="subtitle">Capabilities</span>
        <h3>International Marketing &amp; Creative Toolkit</h3>
      </div>
      <div class="skills-grid">
        <div class="skill-card">
          <div class="skill-icon">🌍</div>
          <h4>International Marketing</h4>
          <p>Global market entry strategy, cross-cultural brand adaptation, consumer behavior analysis, and go-to-market positioning.</p>
        </div>
        <div class="skill-card">
          <div class="skill-icon">🎨</div>
          <h4>Visual &amp; Brand Design</h4>
          <p>Proficient in <strong>Adobe Photoshop, Illustrator, and Lightroom</strong> for brand identity, digital ad creatives, and print collateral.</p>
        </div>
        <div class="skill-card">
          <div class="skill-icon">🎬</div>
          <h4>Video &amp; Digital Storytelling</h4>
          <p>End-to-end video editing and motion storytelling using <strong>Adobe Premiere Pro</strong> for social media and brand campaigns.</p>
        </div>
        <div class="skill-card">
          <div class="skill-icon">📊</div>
          <h4>Commercial Analytics &amp; Ops</h4>
          <p>KPI tracking, sales optimization, customer journey management, and reporting in <strong>Microsoft Excel</strong>.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Experience Section -->
  <section id="experience" class="section bg-light">
    <div class="container">
      <div class="section-header">
        <span class="subtitle">Career Track</span>
        <h3>Professional Experience</h3>
      </div>
      <div class="timeline">
        <div class="timeline-item">
          <div class="timeline-date">2023 – 2025 • London, UK</div>
          <div class="timeline-content">
            <h4>Assistant Manager</h4>
            <h5>LEON Restaurants (Farringdon)</h5>
            <ul>
              <li>Promoted from Team Member to Assistant Manager based on leadership, commercial acumen, and customer focus.</li>
              <li>Drove local commercial performance, customer retention, and daily service KPIs in a high-volume central London market.</li>
              <li>Trained, coached, and motivated multicultural teams to uphold brand standards and deliver consistent customer experiences.</li>
            </ul>
          </div>
        </div>

        <div class="timeline-item">
          <div class="timeline-date">2021 – 2022 • India</div>
          <div class="timeline-content">
            <h4>Client Relations &amp; Front Desk Coordinator (Part-Time)</h4>
            <h5>La Ratatouille</h5>
            <ul>
              <li>Managed customer journeys, reservations, and peak-hour guest communications with personalized service.</li>
              <li>Optimized resource allocation and front-of-house operations while completing full-time university studies.</li>
            </ul>
          </div>
        </div>

        <div class="timeline-item">
          <div class="timeline-date">2020 – 2021 • Bangalore, India</div>
          <div class="timeline-content">
            <h4>Graphic Designer</h4>
            <h5>Netsteds Interior</h5>
            <ul>
              <li>Collaborated directly with the marketing and design teams to produce multi-channel brand communication assets.</li>
              <li>Created visual campaigns, client presentations, and promotional materials using the Adobe Creative Suite.</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Marketing Case Studies / Projects -->
  <section id="projects" class="section">
    <div class="container">
      <div class="section-header">
        <span class="subtitle">Selected Work</span>
        <h3>Marketing &amp; Digital Media Projects</h3>
        <p class="section-desc">Strategic campaigns and creative productions blending international marketing frameworks with visual storytelling.</p>
      </div>
      <div class="projects-grid">
        <article class="project-card">
          <div class="project-tag">Global Brand Strategy</div>
          <h4>European Market Expansion &amp; Localization Playbook</h4>
          <p>
            Comprehensive international marketing strategy analyzing consumer segmentation, competitive positioning, and cultural messaging adaptation for a lifestyle brand entering the French and UK markets.
          </p>
          <div class="project-tools">
            <span>Market Research</span>
            <span>Brand Positioning</span>
            <span>Excel</span>
          </div>
        </article>

        <article class="project-card">
          <div class="project-tag">Digital Campaign &amp; Video</div>
          <h4>Multi-Channel Brand Storytelling &amp; Visual Identity</h4>
          <p>
            Produced cohesive visual campaigns, promotional video edits, and social media assets designed to boost brand awareness and audience engagement across digital touchpoints.
          </p>
          <div class="project-tools">
            <span>Premiere Pro</span>
            <span>Photoshop</span>
            <span>Illustrator</span>
          </div>
        </article>

        <article class="project-card">
          <div class="project-tag">Commercial Design</div>
          <h4>Netsteds Interior Brand Collateral Suite</h4>
          <p>
            Developed client-facing brochures, digital lookbooks, and visual marketing materials in collaboration with internal marketing stakeholders to support lead conversion.
          </p>
          <div class="project-tools">
            <span>Adobe Illustrator</span>
            <span>Lightroom</span>
            <span>B2C Marketing</span>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- Education Section -->
  <section id="education" class="section bg-light">
    <div class="container">
      <div class="section-header">
        <span class="subtitle">Academic Background</span>
        <h3>International Education</h3>
      </div>
      <div class="edu-grid">
        <div class="edu-card">
          <span class="edu-year">2025 – 2026</span>
          <h4>Master in International Marketing</h4>
          <p class="edu-school">ESCE Business School — Paris, France</p>
          <p class="edu-detail">Focus on global marketing strategy, international brand management, and European business environments.</p>
        </div>

        <div class="edu-card">
          <span class="edu-year">2023 – 2025</span>
          <h4>Master in Digital Media</h4>
          <p class="edu-school">London Metropolitan University — London, UK</p>
          <p class="edu-detail">Advanced digital content creation, media strategy, multimedia storytelling, and audience engagement.</p>
        </div>

        <div class="edu-card">
          <span class="edu-year">2018 – 2021</span>
          <h4>Bachelor in Digital Media &amp; Animation</h4>
          <p class="edu-school">St. Joseph’s College — Bangalore, India</p>
          <p class="edu-detail">Foundation in visual communication, graphic design, motion graphics, and digital production.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section contact-section">
    <div class="container contact-grid">
      <div>
        <span class="subtitle">Let's Connect</span>
        <h3>Ready to contribute to your International Marketing team.</h3>
        <p>
          Based in the Paris region (Villiers-le-Bel, 95400) and open to part-time marketing roles, brand management opportunities, and digital campaign collaborations.
        </p>
        <div class="contact-details">
          <p><strong>Email:</strong> <a href="mailto:purushoajith7@gmail.com">purushoajith7@gmail.com</a></p>
          <p><strong>Phone:</strong> <a href="tel:+33743657092">+33 7 43 65 70 92</a></p>
          <p><strong>Location:</strong> Paris Area, France</p>
        </div>
      </div>

      <form class="contact-form" id="contactForm">
        <div class="form-group">
          <label for="name">Your Name</label>
          <input type="text" id="name" required placeholder="Camille Laurent" />
        </div>
        <div class="form-group">
          <label for="email">Email Address</label>
          <input type="email" id="email" required placeholder="camille@company.com" />
        </div>
        <div class="form-group">
          <label for="message">Message</label>
          <textarea id="message" rows="4" required placeholder="Hello Malakiadas, I would love to discuss an opportunity..."></textarea>
        </div>
        <button type="submit" class="btn btn-primary full-width">Send Message</button>
        <p class="form-status" id="formStatus"></p>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container footer-content">
      <p>&copy; <span id="year"></span> Malakiadas Purushothaman. International Marketing Portfolio.</p>
      <a href="#home">Back to top ↑</a>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
```

---

## 2. `style.css`

```css
:root {
  --primary: #0f172a;
  --secondary: #1e293b;
  --accent: #d97706;
  --accent-hover: #b45309;
  --text-main: #1e293b;
  --text-muted: #64748b;
  --bg-white: #ffffff;
  --bg-light: #f8fafc;
  --border: #e2e8f0;
  --radius: 12px;
  --shadow: 0 10px 30px rgba(15, 23, 42, 0.06);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  font-family: 'Inter', sans-serif;
  color: var(--text-main);
  background-color: var(--bg-white);
  line-height: 1.65;
}

.container {
  max-width: 1120px;
  margin: 0 auto;
  padding: 0 24px;
}

/* Navbar */
.navbar {
  position: sticky;
  top: 0;
  z-index: 1000;
  background: rgba(255, 255, 255, 0.94);
  backdrop-filter: blur(10px);
  border-bottom: 1px solid var(--border);
}

.nav-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 74px;
}

.logo {
  font-family: 'Playfair Display', serif;
  font-size: 1.4rem;
  font-weight: 700;
  color: var(--primary);
  text-decoration: none;
}

.logo span {
  color: var(--accent);
}

.nav-links {
  display: flex;
  align-items: center;
  gap: 28px;
}

.nav-links a {
  text-decoration: none;
  color: var(--text-main);
  font-size: 0.95rem;
  font-weight: 500;
  transition: color 0.2s;
}

.nav-links a:hover {
  color: var(--accent);
}

.btn-nav {
  background: var(--primary);
  color: #fff !important;
  padding: 9px 18px;
  border-radius: 8px;
}

.btn-nav:hover {
  background: var(--accent);
}

.hamburger {
  display: none;
  flex-direction: column;
  gap: 5px;
  background: none;
  border: none;
  cursor: pointer;
}

.hamburger span {
  width: 24px;
  height: 2px;
  background: var(--primary);
}

/* Hero */
.hero {
  padding: 80px 0 96px;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.3fr 0.9fr;
  gap: 56px;
  align-items: center;
}

.badge {
  display: inline-block;
  background: #fef3c7;
  color: #92400e;
  font-size: 0.82rem;
  font-weight: 600;
  padding: 6px 14px;
  border-radius: 999px;
  margin-bottom: 18px;
}

.hero h1 {
  font-family: 'Playfair Display', serif;
  font-size: 3.4rem;
  line-height: 1.12;
  color: var(--primary);
  margin-bottom: 14px;
}

.hero h1 span {
  color: var(--accent);
}

.hero h2 {
  font-size: 1.25rem;
  font-weight: 500;
  color: var(--secondary);
  margin-bottom: 18px;
}

.hero p {
  color: var(--text-muted);
  font-size: 1.05rem;
  margin-bottom: 28px;
  max-width: 580px;
}

.hero-buttons {
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
  margin-bottom: 40px;
}

.btn {
  display: inline-block;
  padding: 13px 26px;
  border-radius: 8px;
  font-weight: 600;
  font-size: 0.95rem;
  text-decoration: none;
  cursor: pointer;
  transition: all 0.2s ease;
  border: 2px solid transparent;
}

.btn-primary {
  background: var(--primary);
  color: #fff;
}

.btn-primary:hover {
  background: var(--accent);
}

.btn-outline {
  border-color: var(--border);
  color: var(--primary);
  background: #fff;
}

.btn-outline:hover {
  border-color: var(--primary);
}

.hero-stats {
  display: flex;
  gap: 36px;
  padding-top: 24px;
  border-top: 1px solid var(--border);
}

.hero-stats strong {
  display: block;
  font-size: 1.6rem;
  color: var(--primary);
}

.hero-stats span {
  font-size: 0.85rem;
  color: var(--text-muted);
}

.profile-card {
  position: relative;
  background: var(--bg-light);
  border-radius: 20px;
  padding: 16px;
  box-shadow: var(--shadow);
  border: 1px solid var(--border);
}

.profile-card img {
  width: 100%;
  height: 430px;
  object-fit: cover;
  object-position: center 18%;
  border-radius: 14px;
  display: block;
}

.profile-tag {
  margin-top: 14px;
  padding: 10px 14px;
  background: var(--primary);
  color: #fff;
  border-radius: 10px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.profile-tag span {
  font-weight: 600;
  font-size: 0.9rem;
}

.profile-tag small {
  color: #fbbf24;
  font-size: 0.8rem;
}

/* Sections */
.section {
  padding: 88px 0;
}

.bg-light {
  background-color: var(--bg-light);
}

.section-header {
  margin-bottom: 48px;
}

.subtitle {
  display: inline-block;
  text-transform: uppercase;
  letter-spacing: 0.08em;
  font-size: 0.8rem;
  font-weight: 700;
  color: var(--accent);
  margin-bottom: 8px;
}

.section-header h3 {
  font-family: 'Playfair Display', serif;
  font-size: 2.2rem;
  color: var(--primary);
}

.section-desc {
  color: var(--text-muted);
  margin-top: 8px;
  max-width: 620px;
}

/* About */
.about-grid {
  display: grid;
  grid-template-columns: 1.2fr 1fr;
  gap: 40px;
  align-items: start;
}

.about-text p {
  margin-bottom: 16px;
  color: var(--text-main);
  font-size: 1.03rem;
}

.about-highlights {
  display: grid;
  gap: 20px;
}

.highlight-box {
  background: #fff;
  padding: 24px;
  border-radius: var(--radius);
  border: 1px solid var(--border);
}

.highlight-box h4 {
  margin-bottom: 12px;
  color: var(--primary);
}

.highlight-box ul {
  list-style: none;
}

.highlight-box li {
  padding: 5px 0;
  color: var(--text-muted);
  font-size: 0.95rem;
}

/* Skills */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 24px;
}

.skill-card {
  background: #fff;
  padding: 28px;
  border-radius: var(--radius);
  border: 1px solid var(--border);
  transition: transform 0.2s, box-shadow 0.2s;
}

.skill-card:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow);
}

.skill-icon {
  font-size: 1.8rem;
  margin-bottom: 14px;
}

.skill-card h4 {
  margin-bottom: 10px;
  color: var(--primary);
}

.skill-card p {
  color: var(--text-muted);
  font-size: 0.94rem;
}

/* Experience Timeline */
.timeline {
  display: grid;
  gap: 24px;
}

.timeline-item {
  background: #fff;
  padding: 28px;
  border-radius: var(--radius);
  border: 1px solid var(--border);
  border-left: 4px solid var(--accent);
}

.timeline-date {
  font-size: 0.85rem;
  font-weight: 600;
  color: var(--accent);
  margin-bottom: 6px;
}

.timeline-content h4 {
  font-size: 1.2rem;
  color: var(--primary);
}

.timeline-content h5 {
  font-size: 0.95rem;
  color: var(--text-muted);
  font-weight: 500;
  margin-bottom: 14px;
}

.timeline-content ul {
  padding-left: 18px;
  color: var(--text-main);
}

.timeline-content li {
  margin-bottom: 6px;
  font-size: 0.95rem;
}

/* Projects */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 26px;
}

.project-card {
  background: var(--bg-light);
  padding: 30px;
  border-radius: var(--radius);
  border: 1px solid var(--border);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.project-tag {
  font-size: 0.78rem;
  font-weight: 700;
  text-transform: uppercase;
  color: var(--accent);
  margin-bottom: 10px;
}

.project-card h4 {
  font-size: 1.2rem;
  color: var(--primary);
  margin-bottom: 12px;
}

.project-card p {
  color: var(--text-muted);
  font-size: 0.95rem;
  margin-bottom: 20px;
}

.project-tools {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.project-tools span {
  background: #fff;
  border: 1px solid var(--border);
  padding: 4px 10px;
  border-radius: 6px;
  font-size: 0.8rem;
  font-weight: 500;
  color: var(--secondary);
}

/* Education */
.edu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 24px;
}

.edu-card {
  background: #fff;
  padding: 28px;
  border-radius: var(--radius);
  border: 1px solid var(--border);
}

.edu-year {
  display: inline-block;
  font-size: 0.82rem;
  font-weight: 700;
  color: var(--accent);
  margin-bottom: 8px;
}

.edu-card h4 {
  font-size: 1.15rem;
  color: var(--primary);
  margin-bottom: 6px;
}

.edu-school {
  font-weight: 600;
  font-size: 0.92rem;
  color: var(--secondary);
  margin-bottom: 10px;
}

.edu-detail {
  color: var(--text-muted);
  font-size: 0.92rem;
}

/* Contact */
.contact-section {
  background: var(--primary);
  color: #fff;
}

.contact-section h3 {
  font-family: 'Playfair Display', serif;
  font-size: 2.1rem;
  margin-bottom: 14px;
}

.contact-section p {
  color: #cbd5e1;
}

.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 48px;
  align-items: center;
}

.contact-details {
  margin-top: 24px;
}

.contact-details p {
  margin-bottom: 8px;
  color: #fff;
}

.contact-details a {
  color: #fbbf24;
  text-decoration: none;
}

.contact-form {
  background: #fff;
  color: var(--text-main);
  padding: 32px;
  border-radius: var(--radius);
}

.form-group {
  margin-bottom: 16px;
}

.form-group label {
  display: block;
  font-size: 0.88rem;
  font-weight: 600;
  margin-bottom: 6px;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 11px 14px;
  border: 1px solid var(--border);
  border-radius: 8px;
  font-family: inherit;
  font-size: 0.95rem;
}

.full-width {
  width: 100%;
}

.form-status {
  margin-top: 12px;
  font-size: 0.9rem;
  color: #15803d !important;
  font-weight: 500;
}

/* Footer */
.footer {
  background: #0b1120;
  color: #94a3b8;
  padding: 24px 0;
  font-size: 0.9rem;
}

.footer-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.footer a {
  color: #fbbf24;
  text-decoration: none;
}

/* Responsive */
@media (max-width: 860px) {
  .hero-grid,
  .about-grid,
  .contact-grid {
    grid-template-columns: 1fr;
  }

  .hero h1 {
    font-size: 2.5rem;
  }

  .nav-links {
    display: none;
    position: absolute;
    top: 74px;
    left: 0;
    right: 0;
    background: #fff;
    flex-direction: column;
    padding: 24px;
    border-bottom: 1px solid var(--border);
  }

  .nav-links.active {
    display: flex;
  }

  .hamburger {
    display: flex;
  }
}
```

---

## 3. `script.js`

```javascript
// Set current year in footer
document.getElementById('year').textContent = new Date().getFullYear();

// Mobile navigation toggle
const hamburger = document.getElementById('hamburger');
const navLinks = document.getElementById('navLinks');

hamburger.addEventListener('click', () => {
  navLinks.classList.toggle('active');
});

// Close mobile menu when clicking a link
document.querySelectorAll('.nav-links a').forEach(link => {
  link.addEventListener('click', () => {
    navLinks.classList.remove('active');
  });
});

// Contact form mailto handler (works on static GitHub Pages)
const contactForm = document.getElementById('contactForm');
const formStatus = document.getElementById('formStatus');

contactForm.addEventListener('submit', function (e) {
  e.preventDefault();

  const name = document.getElementById('name').value.trim();
  const email = document.getElementById('email').value.trim();
  const message = document.getElementById('message').value.trim();

  const subject = encodeURIComponent(`Portfolio Inquiry from ${name}`);
  const body = encodeURIComponent(
    `Name: ${name}\nEmail: ${email}\n\nMessage:\n${message}`
  );

  window.location.href = `mailto:purushoajith7@gmail.com?subject=${subject}&body=${body}`;
  formStatus.textContent = 'Opening your email client to send the message...';
  contactForm.reset();
});
```

---

## 4. `README.md`

```markdown
# Malakiadas Purushothaman — International Marketing Portfolio

Personal portfolio website highlighting academic background in **International Marketing** (ESCE Business School, Paris) and **Digital Media** (London Metropolitan University), alongside international work experience across France, the UK, and India.

## Files Included
- `index.html` — Main portfolio structure and content
- `style.css` — Responsive styling and layout
- `script.js` — Mobile navigation and contact form handler
- `profile.jpg` — Portrait photo displayed in the hero section

## How to Publish on GitHub Pages
1. Create a new public repository on GitHub.
2. Upload `index.html`, `style.css`, `script.js`, `README.md`, and `profile.jpg` into the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Branch**, select `main` and `/ (root)`, then click **Save**.
5. Your live portfolio URL will be ready within 1–2 minutes.
```