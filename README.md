
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
        <img src="data:image/webp;base64,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" alt="Portfolio illustrations: Better Data, Brighter Futures and Data, People, Impact">
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
        My skills reflect a mix of existing knowledge, areas where I am building proficiency, and technologies I am continuing to explore through learning and practical projects. I am focused on strengthening the skills I already have while developing new ones to support my growth in Data Analysis and Data Science.
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
