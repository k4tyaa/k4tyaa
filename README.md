## Hello
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Katyayani Singh – Resume</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    :root {
      --pink-bg: #ffe6f2;
      --pink-accent: #e91e63;
      --pink-accent-dark: #c2185b;
      --card-bg: #ffffff;
      --text-main: #333333;
      --text-muted: #555555;
      --border-soft: #f8bbd0;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: radial-gradient(circle at top left, #ffe6f2, #ffffff);
      color: var(--text-main);
      padding: 2rem 1rem;
      display: flex;
      justify-content: center;
    }

    .resume-wrapper {
      max-width: 900px;
      width: 100%;
      background: var(--card-bg);
      border-radius: 18px;
      padding: 2.5rem 2rem;
      box-shadow: 0 18px 40px rgba(233, 30, 99, 0.15);
      border: 1px solid var(--border-soft);
    }

    @media (min-width: 768px) {
      body {
        padding: 3rem;
      }

      .resume-wrapper {
        padding: 3rem 3rem;
      }
    }

    /* Header */
    .header {
      border-bottom: 2px solid var(--border-soft);
      padding-bottom: 1.4rem;
      margin-bottom: 1.6rem;
    }

    .name {
      font-size: 2.3rem;
      letter-spacing: 0.05em;
      text-transform: uppercase;
      color: var(--pink-accent-dark);
      font-weight: 800;
      margin-bottom: 0.25rem;
    }

    .title-tagline {
      font-size: 0.98rem;
      color: var(--text-muted);
      margin-bottom: 0.8rem;
    }

    .contact {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem 1.25rem;
      font-size: 0.9rem;
      color: var(--text-muted);
    }

    .contact a {
      color: var(--pink-accent);
      text-decoration: none;
      font-weight: 500;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    /* Sections */
    .section {
      margin-bottom: 1.6rem;
    }

    .section:last-of-type {
      margin-bottom: 0;
    }

    .section-title {
      font-size: 1.05rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--pink-accent-dark);
      margin-bottom: 0.5rem;
      position: relative;
    }

    .section-title::after {
      content: "";
      position: absolute;
      left: 0;
      bottom: -0.3rem;
      width: 54px;
      height: 3px;
      border-radius: 999px;
      background: linear-gradient(90deg, var(--pink-accent), transparent);
    }

    .summary-text {
      font-size: 0.95rem;
      line-height: 1.6;
      color: var(--text-muted);
      margin-top: 0.6rem;
    }

    /* Entries */
    .entry {
      margin-top: 0.9rem;
    }

    .entry-header {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      gap: 0.25rem 0.75rem;
      font-size: 0.96rem;
    }

    .entry-title {
      font-weight: 600;
      color: var(--text-main);
    }

    .entry-sub {
      font-size: 0.9rem;
      color: var(--pink-accent);
      font-weight: 500;
    }

    .entry-meta {
      font-size: 0.85rem;
      color: var(--text-muted);
      font-style: italic;
    }

    .entry-location {
      font-size: 0.85rem;
      color: var(--text-muted);
    }

    .entry ul {
      margin-top: 0.35rem;
      margin-left: 1.1rem;
      font-size: 0.9rem;
      line-height: 1.5;
      color: var(--text-muted);
    }

    .entry ul li {
      margin-bottom: 0.2rem;
    }

    /* Two-column layout for skills & certs (optional) */
    .two-col {
      display: grid;
      grid-template-columns: 1fr;
      gap: 1.2rem;
    }

    @media (min-width: 680px) {
      .two-col {
        grid-template-columns: 1.2fr 1fr;
      }
    }

    .pill-list {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 0.4rem;
      margin-top: 0.6rem;
    }

    .pill {
      font-size: 0.8rem;
      padding: 0.25rem 0.6rem;
      border-radius: 999px;
      border: 1px solid var(--border-soft);
      color: var(--pink-accent-dark);
      background: #fff7fb;
    }
  </style>
</head>
<body>
  <main class="resume-wrapper">
    <!-- Header -->
    <header class="header">
      <h1 class="name">Katyayani Singh</h1>
      <p class="title-tagline">
        Third-year Psychology Student • Clinical & Behavioural Neuroscience Enthusiast • Mental Health & Community Engagement
      </p>
      <div class="contact">
        <span>Vancouver, BC</span>
        <span><a href="mailto:katyayani.singh21@gmail.com">katyayani.singh21@gmail.com</a></span>
        <span>(778) 231-684</span>
        <span><a href="https://www.linkedin.com/in/iamkatya" target="_blank" rel="noreferrer">LinkedIn: @iamkatya</a></span>
      </div>
    </header>

    <!-- Summary -->
    <section class="section">
      <h2 class="section-title">Summary</h2>
      <p class="summary-text">
        Third-year undergraduate Psychology major at the University of British Columbia, with keen interests in clinical psychology,
        behavioural neuroscience, and mental health. Experienced in supporting structured community programs, fostering inclusive
        environments, and collaborating with multidisciplinary teams. Skilled in cross-cultural communication, empathy-driven teaching,
        and research ethics. Actively seeking opportunities to contribute to psychology, well-being, and academic engagement programs.
      </p>
    </section>

    <!-- Education -->
    <section class="section">
      <h2 class="section-title">Education</h2>
      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Bachelor of Arts, Psychology (Major), Philosophy (Minor)</div>
            <div class="entry-sub">University of British Columbia</div>
          </div>
          <div class="entry-meta">2022 – Ongoing · Vancouver, BC</div>
        </div>
        <p class="summary-text" style="margin-top:0.4rem;">
          Relevant coursework: Research Methods; Brain Dysfunction and Recovery; Behavioural Disorders; Environmental Psychology;
          Drugs, Brain and Society.
        </p>
      </div>
    </section>

    <!-- Research Projects -->
    <section class="section">
      <h2 class="section-title">Research Projects</h2>
      <div class="entry">
        <div class="entry-header">
          <div class="entry-title">
            Messaging Matters? Effects of Framing on Willingness to Reduce Food Waste
          </div>
          <div class="entry-meta">2025</div>
        </div>
        <div class="entry-location">
          Final research report submitted to UBC SEEDS Sustainability Program (PSYC 421: Environmental Psychology)
        </div>
      </div>
    </section>

    <!-- Experience -->
    <section class="section">
      <h2 class="section-title">Experience</h2>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Content Creator</div>
            <div class="entry-sub">UBC Psychology Students’ Association (PSA)</div>
          </div>
          <div class="entry-meta">September 2024 – Present · Vancouver, BC</div>
        </div>
        <ul>
          <li>Develop and design engaging digital content (posts, reels, and stories) for PSA’s social media platforms.</li>
          <li>Translate complex psychological concepts into accessible, student-friendly visual and written materials.</li>
          <li>Increased audience engagement by approximately 70% using consistent scheduling and data-driven insights.</li>
          <li>Supported promotion of major PSA initiatives such as Psych Night, graduate school panels, and Mental Health Awareness Week.</li>
        </ul>
      </div>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Parent &amp; Tot Program Assistant</div>
            <div class="entry-sub">Wesbrook Community Centre</div>
          </div>
          <div class="entry-meta">Dec 2024 – Mar 2025 · Vancouver, BC</div>
        </div>
        <ul>
          <li>Supported cognitive and social development in early childhood through structured, play-based sessions.</li>
          <li>Adapted activities based on engagement and developmental needs, aligned with inclusive learning principles.</li>
          <li>Supported caregivers with behaviour challenges through empathy, active listening, and situational feedback.</li>
          <li>Applied strong communication and time-management skills to assist with early learning outcomes.</li>
        </ul>
      </div>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Marketing &amp; Research Intern</div>
            <div class="entry-sub">Jackpot Consulting</div>
          </div>
          <div class="entry-meta">May 2025 – Aug 2025 · Remote/UBC</div>
        </div>
        <ul>
          <li>Supported branding and content strategy for internal projects and client pitches.</li>
          <li>Conducted research on Gen-Z consumer behaviour and market trends for presentation decks.</li>
          <li>Helped organize digital content and workflows using Notion, Microsoft Suite, Canva, and Adobe Creative Cloud.</li>
          <li>Collaborated on information architecture and campaign material organization across digital platforms.</li>
        </ul>
      </div>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Psychiatry Clinic Observer</div>
            <div class="entry-sub">Private Practice of Dr. Kuldeep Singh (NIMHANS-trained Psychiatrist)</div>
          </div>
          <div class="entry-meta">Jun 2024 – Jul 2024 · Bengaluru, India</div>
        </div>
        <ul>
          <li>Completed a one-month clinical observership, observing diagnostic interviews and treatment planning.</li>
          <li>Engaged in follow-up discussions on complex cases involving mood, anxiety, and neurodevelopmental disorders.</li>
          <li>Strictly adhered to patient confidentiality and clinic protocols.</li>
          <li>Reflected on social, cultural, and psychological dimensions of mental health care in India.</li>
        </ul>
      </div>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Research Volunteer</div>
            <div class="entry-sub">Raphael Ryder-Cheshire Home</div>
          </div>
          <div class="entry-meta">Apr 2022 – Jan 2023 · India</div>
        </div>
        <ul>
          <li>Worked with children with disabilities in rehabilitation settings, tailoring engagement to varied needs.</li>
          <li>Collaborated with multidisciplinary teams on personalized care and development strategies.</li>
          <li>Facilitated therapeutic activities focused on motor and cognitive development.</li>
          <li>Developed empathy, behavioural observation, and mental health awareness skills.</li>
        </ul>
      </div>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Peer Tutor</div>
            <div class="entry-sub">Online &amp; In-person</div>
          </div>
          <div class="entry-meta">May 2020 – Sept 2022 · India</div>
        </div>
        <ul>
          <li>Tutored students aged 13–18 from underserved backgrounds in English, Mathematics, Economics, Psychology, and History.</li>
          <li>Fostered academic confidence and long-term learning habits in students facing financial barriers.</li>
          <li>Developed lesson plans, feedback systems, and adaptive teaching styles.</li>
        </ul>
      </div>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Sales &amp; Inventory Assistant</div>
            <div class="entry-sub">Thrift and Fund Thrift Store, Low Entropy Foundation</div>
          </div>
          <div class="entry-meta">May 2023 – Jul 2023 · Coquitlam, BC</div>
        </div>
        <ul>
          <li>Maintained accurate inventory and organized retail space to improve operational efficiency.</li>
          <li>Provided customer service and managed cash transactions with high attention to detail.</li>
          <li>Implemented organizational strategies that improved event efficiency and workflow.</li>
        </ul>
      </div>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">Active Member – Environmental Initiatives</div>
            <div class="entry-sub">MAD by BTD (Making a Difference by Being the Difference)</div>
          </div>
          <div class="entry-meta">2019 – 2023 · Dehradun, India</div>
        </div>
        <ul>
          <li>Contributed to environmental outreach through community cleanups, tree plantations, and awareness campaigns.</li>
          <li>Supported planning and execution of Madathon, India’s largest plastic-free marathon.</li>
          <li>Coordinated logistics and volunteers for large-scale sustainability events.</li>
        </ul>
      </div>

      <div class="entry">
        <div class="entry-header">
          <div>
            <div class="entry-title">SEEDS Sustainability Research (PSYC 421)</div>
            <div class="entry-sub">University of British Columbia</div>
          </div>
          <div class="entry-meta">Jan 2025 – Apr 2025 · Vancouver, BC</div>
        </div>
        <ul>
          <li>Co-led a CAP 2030–aligned study on how message framing influences willingness to reduce food waste.</li>
          <li>Co-designed a Qualtrics survey for 260+ participants across UBC Vancouver.</li>
          <li>Co-wrote executive summary, hypotheses, methods, and discussion for the final SEEDS report.</li>
          <li>Translated environmental psychology theory into applied recommendations for AMS-aligned campaigns.</li>
        </ul>
      </div>
    </section>

    <!-- Skills + Certifications -->
    <section class="section">
      <div class="two-col">
        <div>
          <h2 class="section-title">Skills</h2>
          <ul class="pill-list">
            <li class="pill">Research ethics (TCPS 2)</li>
            <li class="pill">Data collection</li>
            <li class="pill">Participant observation</li>
            <li class="pill">Academic literature review</li>
            <li class="pill">Report writing</li>
            <li class="pill">Canvas &amp; MS Teams</li>
            <li class="pill">Google Workspace</li>
            <li class="pill">Basic statistical analysis</li>
            <li class="pill">Microsoft Office Suite</li>
            <li class="pill">Discussion facilitation</li>
            <li class="pill">Empathetic listening</li>
            <li class="pill">Cross-cultural communication</li>
            <li class="pill">Mentoring</li>
            <li class="pill">Time management</li>
            <li class="pill">Virtual coordination</li>
            <li class="pill">Mental health awareness</li>
            <li class="pill">Anxiety &amp; youth development</li>
            <li class="pill">CPR/AED certified</li>
          </ul>
        </div>

        <div>
          <h2 class="section-title">Certifications</h2>
          <div class="entry">
            <ul>
              <li>Schizophrenia – Wesleyan University (Jul 2025)</li>
              <li>Fundamental Neuroscience for Neuroimaging &amp; Principles of fMRI – Johns Hopkins University (May 2025)</li>
              <li>Tri-Council Policy Statement (TCPS 2) – Government of Canada (May 2025)</li>
              <li>CPR/AED Level C – Canadian Red Cross, BC (Dec 2024)</li>
              <li>Anxiety and Related Disorders – American Psychological Association (Oct 2024)</li>
            </ul>
          </div>
        </div>
      </div>
    </section>
  </main>
</body>
</html>
