# HI, Welcome to my profile 

<img width="1280" height="640" alt="image" src="https://github.com/user-attachments/assets/f7e8f4cd-39d7-4a46-ab05-bc313cbac06c" />
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Moji's portfolio: IT graduate exploring Data Science, Data Analysis and Data Quality.">
  <title>Moji | Data, Analysis & Impact</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:ital,wght@1,600&display=swap" rel="stylesheet">

  <style>
    :root {
      --ink: #203746;
      --teal: #147967;
      --muted: #617487;
      --line: #e2e9e7;
      --soft: #eff6f2;
      --white: #ffffff;
      --max-width: 1120px;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
      scroll-padding-top: 85px;
    }

    body {
      background: var(--white);
      color: var(--ink);
      font-family: "DM Sans", sans-serif;
      font-size: 15px;
      line-height: 1.7;
    }

    a {
      color: var(--teal);
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .container {
      width: min(100% - 44px, var(--max-width));
      margin: 0 auto;
    }

    header {
      background: rgba(255,255,255,.96);
      border-bottom: 1px solid #f0f2f0;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav {
      min-height: 70px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 25px;
    }

    .brand {
      font-family: "Playfair Display", serif;
      font-size: 30px;
      font-style: italic;
      color: var(--ink);
    }

    .nav-links {
      display: flex;
      flex-wrap: wrap;
      gap: 25px;
      font-size: 13px;
    }

    .nav-links a {
      color: var(--ink);
    }

    .hero {
      display: grid;
      grid-template-columns: 1.05fr .95fr;
      align-items: center;
      gap: 40px;
      padding-top: 45px;
      padding-bottom: 42px;
      min-height: 380px;
    }

    .eyebrow {
      color: var(--teal);
      text-transform: uppercase;
      font-size: 11px;
      font-weight: 700;
      letter-spacing: 2px;
      margin-bottom: 12px;
    }

    h1 {
      font-size: clamp(38px, 5vw, 59px);
      line-height: 1.12;
      letter-spacing: -2px;
      margin-bottom: 18px;
    }

    h1 span {
      color: var(--teal);
    }

    .hero-intro {
      font-size: 16px;
      font-weight: 500;
      line-height: 1.65;
      margin-bottom: 13px;
    }

    .hero-description {
      color: var(--muted);
      max-width: 510px;
      margin-bottom: 24px;
    }

    .actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .button {
      display: inline-block;
      border: 1px solid var(--teal);
      border-radius: 30px;
      padding: 10px 20px;
      font-size: 13px;
      font-weight: 700;
    }

    .button.primary {
      background: var(--teal);
      color: white;
    }

    .button.secondary {
      color: var(--teal);
      background: white;
    }

    .hero-visual {
      min-height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #f4f8f5;
      border-radius: 48% 52% 40% 60% / 48% 42% 58% 52%;
      overflow: hidden;
    }

    .hero-visual img {
      display: block;
      width: 100%;
      height: 340px;
      object-fit: cover;
      object-position: center;
    }

    .image-placeholder {
      padding: 30px;
      text-align: center;
      color: var(--muted);
    }

    section {
      padding: 37px 0;
      border-top: 1px solid var(--line);
    }

    .section-heading {
      font-size: 27px;
      line-height: 1.3;
      margin-bottom: 8px;
    }

    .section-intro {
      color: var(--muted);
      margin-bottom: 25px;
    }

    .about-grid {
      display: grid;
      grid-template-columns: 1.1fr .9fr;
      align-items: center;
      gap: 65px;
    }

    .about-note {
      background: var(--soft);
      padding: 30px;
      border-radius: 8px;
      color: var(--teal);
      font-size: 20px;
      line-height: 1.5;
      text-align: center;
    }

    .text-link {
      display: inline-block;
      margin-top: 15px;
      font-weight: 700;
      font-size: 13px;
    }

    .project-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 40px;
    }

    .project {
      padding: 5px 22px 12px 0;
    }

    .project + .project {
      border-left: 1px solid var(--line);
      padding-left: 35px;
    }

    .label {
      display: inline-block;
      background: var(--soft);
      color: var(--teal);
      padding: 3px 11px;
      border-radius: 20px;
      font-size: 11px;
      font-weight: 700;
      margin-bottom: 12px;
    }

    h3 {
      font-size: 17px;
      line-height: 1.45;
      margin-bottom: 8px;
    }

    .project p,
    .job p,
    .education-item p {
      color: var(--muted);
      font-size: 13px;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 13px;
      color: var(--muted);
      font-size: 12px;
    }

    .experience-grid {
      display: grid;
      grid-template-columns: 1.1fr .9fr;
      gap: 35px;
    }

    .job {
      padding: 18px 0;
      border-bottom: 1px solid var(--line);
    }

    .job:first-child {
      padding-top: 0;
    }

    .job:last-child {
      border-bottom: 0;
    }

    .date {
      color: var(--teal);
      font-size: 12px;
      margin: 3px 0 8px;
    }

    ul.detail-list {
      padding-left: 19px;
      margin-top: 8px;
      color: var(--muted);
      font-size: 13px;
    }

    .side-column {
      padding-left: 30px;
      border-left: 1px solid var(--line);
    }

    .side-block {
      margin-bottom: 25px;
    }

    .side-block:last-child {
      margin-bottom: 0;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 35px;
    }

    .skill-group {
      padding: 5px 0 20px;
    }

    .skill-group h3 {
      color: var(--teal);
    }

    .skill-group p {
      color: var(--muted);
      font-size: 13px;
    }

    .skill-status {
      display: inline-block;
      margin: 8px 0;
      font-size: 11px;
      font-weight: 700;
      color: var(--teal);
      text-transform: uppercase;
      letter-spacing: .7px;
    }

    .skill-list {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 7px 15px;
      color: var(--muted);
      font-size: 13px;
    }

    .skill-list li::before {
      content: "• ";
      color: var(--teal);
    }

    .education-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 35px;
    }

    .education-item {
      padding: 13px 0;
      border-bottom: 1px solid var(--line);
    }

    .education-item:last-child {
      border-bottom: 0;
    }

    .research-note {
      margin-top: 18px;
      padding: 20px;
      background: #f5f8f6;
      border-left: 3px solid var(--teal);
    }

    .goals {
      background: var(--soft);
      border-radius: 10px;
      padding: 28px;
      display: grid;
      grid-template-columns: .8fr 1fr 1fr;
      gap: 28px;
      align-items: start;
    }

    .goal h3 {
      color: var(--teal);
    }

    .goal p,
    .goal li {
      color: var(--muted);
      font-size: 13px;
    }

    .goal ul {
      padding-left: 18px;
    }

    .contact {
      text-align: center;
      padding: 45px 0;
    }

    .contact p {
      color: var(--muted);
      margin: 10px 0 20px;
    }

    footer {
      border-top: 1px solid var(--line);
      padding: 20px 0;
      color: var(--muted);
      font-size: 12px;
    }

    .footer-inner {
      display: flex;
      justify-content: space-between;
      gap: 15px;
      flex-wrap: wrap;
      align-items: center;
    }

    @media (max-width: 760px) {
      .nav-links {
        gap: 12px;
        justify-content: flex-end;
      }

      nav {
        align-items: flex-start;
        padding: 15px 0;
      }

      .hero,
      .about-grid,
      .project-grid,
      .experience-grid,
      .skills-grid,
      .education-grid,
      .goals {
        grid-template-columns: 1fr;
      }

      .hero {
        gap: 25px;
        padding-top: 30px;
      }

      .hero-visual {
        min-height: 220px;
      }

      .hero-visual img {
        height: 260px;
      }

      .project + .project {
        border-left: 0;
        border-top: 1px solid var(--line);
        padding: 25px 0 0;
      }

      .side-column {
        border-left: 0;
        padding-left: 0;
        border-top: 1px solid var(--line);
        padding-top: 25px;
      }

      .about-grid {
        gap: 25px;
      }

      .goals {
        gap: 20px;
      }

      h1 {
        letter-spacing: -1px;
      }
    }
  </style>
</head>

<body>

<header>
  <nav class="container">
    <a class="brand" href="#home">Moji</a>
    <div class="nav-links">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#experience">Experience</a>
      <a href="#education">Education</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>
</header>

<main>
  <div class="container">
    <section class="hero" id="home" style="border-top:0">
      <div>
        <p class="eyebrow">Data · Analysis · Impact</p>
        <h1>Hey, I'm <span>Moji</span></h1>

        <p class="hero-intro">
          I'm an IT graduate exploring the world of data, technology,
          and the ideas that make a real difference.
        </p>

        <p class="hero-description">
          I'm beginning my Data Science journey with Data Analysis and
          Data Quality, refreshing my Python and SQL skills, and turning
          what I learn into practical projects. I love a good puzzle,
          a new challenge, and discovering what the details can tell us.
        </p>

        <div class="actions">
          <a class="button primary" href="#projects">View My Projects</a>
          <a class="button secondary" href="#about">Get to Know Me</a>
        </div>
      </div>

      <div class="hero-visual">
        <!-- Add your portrait to assets/moji-hero.png -->
        <img src="assets/moji-hero.png"
             alt="Moji working at her laptop"
             onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
        <div class="image-placeholder" style="display:none">
          Add your portfolio portrait to the assets folder
          and name it moji-hero.png.
        </div>
      </div>
    </section>

    <section id="about">
      <div class="about-grid">
        <div>
          <h2 class="section-heading">About Me</h2>
          <p>
            I'm an Information Technology graduate interested in how
            technology and data can help people make better-informed
            decisions. My academic background, professional experience,
            and research have shaped my curiosity about solving problems
            and finding practical ways to use information.
          </p>
          <p style="margin-top:12px">
            I'm especially interested in education and student success,
            data quality, and the responsible use of Artificial
            Intelligence in higher education. I'm building my skills
            step by step and learning by applying them to real questions.
          </p>
          <a class="text-link" href="#research">Explore my research</a>
        </div>

        <div class="about-note">
          Curious about the problem.
          <br>
          Interested in the details.
          <br>
          Always learning.
        </div>
      </div>
    </section>

    <section id="projects">
      <h2 class="section-heading">Featured Projects</h2>
      <p class="section-intro">
        Early ideas I'm developing into practical portfolio projects.
      </p>

      <div class="project-grid">
        <article class="project">
          <span class="label">Phase 2 · Planned</span>
          <h3>Student Progression Through Data Quality</h3>
          <p>
            Explore how accurate, complete, and consistent data can help
            higher education institutions understand student progression
            and identify where additional support may be needed.
          </p>
          <div class="tags">
            <span>SQL</span><span>Data Cleaning</span>
            <span>Education</span><span>Visualisation</span>
          </div>
        </article>

        <article class="project">
          <span class="label">Phase 2 · Planned</span>
          <h3>AI in Higher Education: Opportunity and Responsibility</h3>
          <p>
            Build on my academic research by exploring how AI may support
            teaching, administration, and student success, while
            considering data quality, privacy, and responsible use.
          </p>
          <div class="tags">
            <span>Research</span><span>Data Analysis</span>
            <span>AI Ethics</span><span>Communication</span>
          </div>
        </article>
      </div>
    </section>

    <section id="experience">
      <h2 class="section-heading">Experience</h2>
      <p class="section-intro">
        Building on experience across IT, presales, administration, and mentoring.
      </p>

      <div class="experience-grid">
        <div>
          <article class="job">
            <h3>New Island Technologies</h3>
            <p>BMC Netreo Presales Consultant and AIOps Internship Mentor</p>
            <p class="date">July 2024 – September 2026</p>
            <ul class="detail-list">
              <li>Supported partner prospecting and business development.</li>
              <li>Assisted with solution demonstrations and proof-of-concept activities.</li>
              <li>Contributed to marketing content and customer events.</li>
              <li>Mentored AIOps interns in Linux, networking, monitoring, and related topics.</li>
            </ul>
          </article>

          <article class="job">
            <h3>CBI-Electric African Cables</h3>
            <p>HR and Administration</p>
            <p class="date">August 2019 – November 2022</p>
            <p>
              Supported HR administration, recruitment, payroll-related
              processes, invoices, contracts, employee records, and
              learnership coordination.
            </p>
          </article>
        </div>

        <div class="side-column">
          <div class="side-block">
            <h3>Professional strengths</h3>
            <p>
              Communication, organisation, problem-solving, mentoring,
              collaboration, and working with different stakeholders.
            </p>
          </div>

          <div class="side-block">
            <h3>Technology exposure</h3>
            <p>
              BMC Helix Network Management (Netreo), AIOps, IT operations
              monitoring, demonstrations, and technical enablement.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section id="skills">
      <h2 class="section-heading">Skills</h2>
      <p class="section-intro">
        My current foundation and the capabilities I'm working towards.
      </p>

      <div class="skills-grid">
        <div>
          <div class="skill-group">
            <h3>Current foundation</h3>
            <span class="skill-status">Skills and experience to build on</span>
            <ul class="skill-list">
              <li>Information Technology fundamentals</li>
              <li>Problem-solving</li>
              <li>Communication</li>
              <li>Teamwork and collaboration</li>
              <li>Research and information gathering</li>
              <li>Excel and administrative data handling</li>
              <li>Technical presentations</li>
              <li>Git and GitHub fundamentals</li>
            </ul>
          </div>

          <div class="skill-group">
            <h3>Refreshing and developing</h3>
            <span class="skill-status">Current learning focus</span>
            <ul class="skill-list">
              <li>Python</li>
              <li>SQL</li>
              <li>Data analysis</li>
              <li>Data cleaning and quality</li>
              <li>Exploratory data analysis</li>
              <li>Data visualisation</li>
            </ul>
          </div>
        </div>

        <div>
          <div class="skill-group">
            <h3>Skills to develop for Data Science</h3>
            <span class="skill-status">Future learning roadmap</span>
            <ul class="skill-list">
              <li>Statistics and probability</li>
              <li>Advanced SQL and database concepts</li>
              <li>Python libraries: Pandas and NumPy</li>
              <li>Visualisation with Matplotlib and Seaborn</li>
              <li>Power BI or Tableau</li>
              <li>Data wrangling and feature preparation</li>
              <li>Machine learning fundamentals</li>
              <li>Model evaluation and validation</li>
              <li>Data storytelling and presentation</li>
              <li>Git version control and project documentation</li>
              <li>Data privacy, ethics, and responsible AI</li>
              <li>Cloud and big data fundamentals</li>
            </ul>
          </div>

          <div class="skill-group">
            <h3>Professional skills to strengthen</h3>
            <ul class="skill-list">
              <li>Critical thinking</li>
              <li>Analytical reasoning</li>
              <li>Asking clear questions</li>
              <li>Explaining findings to non-technical audiences</li>
              <li>Time management</li>
              <li>Continuous learning</li>
            </ul>
          </div>
        </div>
      </div>

      <p style="margin-top:15px;color:var(--muted);font-size:12px">
        The development list is a roadmap, not a claim that I have already
        mastered these tools. I plan to build proficiency through study
        and practical projects.
      </p>
    </section>

    <section id="education">
      <h2 class="section-heading">Education</h2>
      <p class="section-intro">
        The academic foundation behind my interest in technology and data.
      </p>

      <div class="education-grid">
        <div>
          <article class="education-item">
            <h3>Postgraduate Diploma in Information Technology</h3>
            <p>Vaal University of Technology</p>
            <p class="date">2022 – 2023</p>
          </article>

          <article class="education-item">
            <h3>Advanced Diploma in Information Technology</h3>
            <p>Vaal University of Technology</p>
            <p class="date">2021 – 2022</p>
          </article>

          <article class="education-item">
            <h3>Diploma in Information Technology</h3>
            <p>Vaal University of Technology</p>
            <p class="date">2018 – 2021 · Cum Laude</p>
          </article>
        </div>

        <div>
          <article class="education-item">
            <h3>HR Management and Support Certificate</h3>
            <p>MacCauvlei</p>
            <p class="date">2023 – 2024</p>
          </article>

          <article class="education-item">
            <h3>BMC Helix Network Management (Netreo)</h3>
            <p>Advanced Training</p>
          </article>

          <article class="education-item">
            <h3>BMC Helix AIOps</h3>
            <p>Advanced Training and AIOps Bootcamp</p>
          </article>

          <article class="education-item">
            <h3>BMC Helix Partner Sales Certification</h3>
            <p>Foundation</p>
          </article>
        </div>
      </div>
    </section>

    <section id="research">
      <h2 class="section-heading">Research & Curiosity</h2>

      <div class="research-note">
        <h3>The Impact of Artificial Intelligence in Higher Education Institutions</h3>
        <p>
          My postgraduate research at the Vaal University of Technology
          explored the impact of AI in higher education. It contributed to
          my interest in how technology can support institutions, educators,
          and students, and raised questions about the quality and
          responsible use of data in decision-making.
        </p>
        <p style="margin-top:10px">
          I want to build on this foundation by learning how data analysis
          can help investigate patterns, understand student progression,
          and provide useful evidence for educational decisions.
        </p>
      </div>
    </section>

    <section id="goals">
      <h2 class="section-heading">Learning & Goals</h2>
      <p class="section-intro">
        Small, achievable steps towards a stronger data portfolio.
      </p>

      <div class="goals">
        <div class="goal">
          <h3>My direction</h3>
          <p>
            Develop practical data analysis and data quality skills,
            then expand my knowledge towards Data Science.
          </p>
        </div>

        <div class="goal">
          <h3>Short term · 30 days</h3>
          <ul>
            <li>Refresh Python and SQL fundamentals.</li>
            <li>Practise cleaning a small dataset.</li>
            <li>Document the process and findings.</li>
          </ul>
        </div>

        <div class="goal">
          <h3>Next 6 months</h3>
          <ul>
            <li>Publish practical projects on GitHub.</li>
            <li>Strengthen statistics and visualisation.</li>
            <li>Learn machine learning fundamentals.</li>
            <li>Communicate findings clearly.</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <h2 class="section-heading">Let's Connect</h2>
      <p>
        I'm learning, growing, and exploring where data can take me.
      </p>
      <div class="actions" style="justify-content:center">
        <!-- Replace the example links with your actual profile URLs -->
        <a class="button primary" href="https://github.com/YOUR-USERNAME">
          GitHub
        </a>
        <a class="button secondary" href="https://www.linkedin.com/in/YOUR-LINKEDIN/">
          LinkedIn
        </a>
      </div>
    </section>
  </div>
</main>

<footer>
  <div class="container footer-inner">
    <span class="brand">Moji</span>
    <span>Data · Growth · Impact</span>
    <span>Learning one project at a time.</span>
  </div>
</footer>

</body>
</html>
