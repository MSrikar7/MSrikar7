<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Venkata Srikar Manikonda | Data Scientist</title>
  <link rel="stylesheet" href="styles.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap"
    rel="stylesheet"
  />
</head>
<body>
  <!-- Top Navigation -->
  <header class="site-header">
    <div class="container nav-container">
      <div class="logo">
        <span class="logo-accent">S</span>rikar
      </div>
      <nav class="nav-links" id="navLinks">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#research">Research</a>
        <a href="#experience">Experience</a>
        <a href="#contact">Contact</a>
      </nav>
      <button class="nav-toggle" id="navToggle" aria-label="Toggle navigation">
        ☰
      </button>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-overlay"></div>
    <div class="container hero-content">
      <div class="hero-text">
        <p class="hero-tag">Data Science • AI • Analytics</p>
        <h1>
          Hi, I’m
          <span class="gradient-text">Venkata Srikar Manikonda</span>
        </h1>
        <p class="hero-subtitle">
          Data Scientist with 1.5+ years of experience and 1.5 years as a Data Analyst Intern at Evolv Technologies. I build
          AI-driven analytics, predictive models, and scalable data solutions that turn raw data into intelligent products and
          decisions.
        </p>
        <div class="hero-buttons">
          <a href="#projects" class="btn primary-btn">View Projects</a>
          <a href="#contact" class="btn outline-btn">Get in Touch</a>
        </div>
        <div class="hero-tags">
          <span>Machine Learning</span>
          <span>EDA & Analytics</span>
          <span>LLMs & Local Inference</span>
          <span>MLOps & Deployment</span>
        </div>
      </div>
      <div class="hero-panel">
        <div class="hero-card">
          <p class="hero-card-label">Data Scientist</p>
          <p class="hero-card-main">AI & Analytics</p>
          <p class="hero-card-sub">ML • Data Pipelines • Insights</p>
        </div>
      </div>
    </div>
  </section>

  <!-- About -->
  <section id="about" class="section">
    <div class="container">
      <h2 class="section-title">About Me</h2>
      <div class="section-body">
        <p>
          I’m a <strong>Data Scientist</strong> with a blend of
          <span class="highlight">machine learning, analytics, and software engineering</span>.
          I have 1.5+ years of experience as a Data Scientist and 1.5 years as a Data Analyst Intern at Evolv Technologies,
          working end-to-end across data cleaning, feature engineering, model development, evaluation, and insight communication.
        </p>
        <p>
          My academic research explores
          <span class="highlight">GANs, transfer learning, 3D face modelling, and medical imaging</span>.
          I enjoy building systems that connect ML models with real users—whether it’s an AI study assistant powered by a local
          LLM or analytics pipelines that drive data-informed strategies.
        </p>
      </div>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills" class="section alt-section">
    <div class="container">
      <h2 class="section-title">Skills</h2>
      <div class="skills-grid">
        <div class="card">
          <h3>Languages</h3>
          <div class="pill-row">
            <span class="pill">Python</span>
            <span class="pill">SQL</span>
            <span class="pill">Java</span>
            <span class="pill">JavaScript</span>
          </div>
        </div>

        <div class="card">
          <h3>ML & Data Science</h3>
          <div class="pill-row">
            <span class="pill">EDA</span>
            <span class="pill">Feature Engineering</span>
            <span class="pill">Statistical Analysis</span>
            <span class="pill">Predictive Modeling</span>
            <span class="pill">Model Evaluation</span>
            <span class="pill">Time Series Forecasting</span>
          </div>
        </div>

        <div class="card">
          <h3>Libraries & Frameworks</h3>
          <div class="pill-row">
            <span class="pill">pandas</span>
            <span class="pill">NumPy</span>
            <span class="pill">scikit-learn</span>
            <span class="pill">TensorFlow</span>
            <span class="pill">PyTorch</span>
          </div>
        </div>

        <div class="card">
          <h3>Backend & Systems</h3>
          <div class="pill-row">
            <span class="pill">REST APIs</span>
            <span class="pill">Microservices</span>
            <span class="pill">System Design</span>
            <span class="pill">OAuth</span>
            <span class="pill">JWT</span>
          </div>
        </div>

        <div class="card">
          <h3>Databases & Cloud</h3>
          <div class="pill-row">
            <span class="pill">MySQL</span>
            <span class="pill">PostgreSQL</span>
            <span class="pill">MongoDB</span>
            <span class="pill">AWS</span>
            <span class="pill">Azure</span>
            <span class="pill">GCP</span>
          </div>
        </div>

        <div class="card">
          <h3>Tools, MLOps & BI</h3>
          <div class="pill-row">
            <span class="pill">Git & GitHub</span>
            <span class="pill">Docker</span>
            <span class="pill">CI/CD</span>
            <span class="pill">Linux</span>
            <span class="pill">ML Pipelines</span>
            <span class="pill">Model Deployment</span>
            <span class="pill">Power BI</span>
            <span class="pill">Tableau</span>
            <span class="pill">Matplotlib</span>
            <span class="pill">Seaborn</span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="section">
    <div class="container">
      <h2 class="section-title">Projects</h2>
      <div class="card-grid">
        <!-- Project 1 -->
        <article class="card project-card">
          <div class="card-header">
            <h3>Latent Image Animator (LIA)</h3>
            <span class="badge">Deep Learning • Generative Models</span>
          </div>
          <p class="card-subtitle">
            Neural animation model that generates realistic facial motion from static images using latent representation learning
            and motion transfer.
          </p>
          <ul class="card-list">
            <li>Designed an end-to-end deep learning pipeline to animate faces from single images using latent motion transfer.</li>
            <li>Used CNNs for facial feature extraction and GAN-style architectures for realistic frame synthesis.</li>
            <li>Implemented GPU-backed training workflows to improve coherence and temporal consistency in the animations.</li>
          </ul>
          <div class="pill-row">
            <span class="pill small">Python</span>
            <span class="pill small">PyTorch / TensorFlow</span>
            <span class="pill small">OpenCV</span>
            <span class="pill small">NumPy</span>
            <span class="pill small">pandas</span>
            <span class="pill small">CUDA</span>
            <span class="pill small">Jupyter</span>
          </div>
        </article>

        <!-- Project 2 -->
        <article class="card project-card">
          <div class="card-header">
            <h3>AI Study Buddy – Local LLM Web App</h3>
            <span class="badge">LLM • Web App • Local Inference</span>
          </div>
          <p class="card-subtitle">
            AI-powered study assistant that uses a locally hosted LLM to answer questions, explain concepts, and support interactive learning.
          </p>
          <ul class="card-list">
            <li>
              Architected a modular backend that integrates a local LLM (Ollama / GPT4All-style) for real-time question answering and explanations.
            </li>
            <li>Built REST endpoints and a chat-style interface for session-based study assistance.</li>
            <li>
              Designed the system for low-latency inference and future extension with personalization, recommendations, and topic-wise tracking.
            </li>
          </ul>
          <div class="pill-row">
            <span class="pill small">Python</span>
            <span class="pill small">FastAPI / Flask</span>
            <span class="pill small">Local LLM</span>
            <span class="pill small">JavaScript</span>
            <span class="pill small">HTML/CSS</span>
            <span class="pill small">Docker</span>
            <span class="pill small">Linux</span>
          </div>
        </article>

        <!-- Project 3 -->
        <article class="card project-card">
          <div class="card-header">
            <h3>Student Performance Analysis</h3>
            <span class="badge">Analytics • Predictive Modeling</span>
          </div>
          <p class="card-subtitle">
            Predictive analytics pipeline to understand factors influencing student performance and identify at-risk students.
          </p>
          <ul class="card-list">
            <li>Performed EDA on academic and behavioral data to uncover patterns, trends, and correlations.</li>
            <li>
              Built classification and regression models (logistic regression, random forest, gradient boosting) to predict performance bands.
            </li>
            <li>Used feature importance and interpretability methods to communicate key performance drivers to stakeholders.</li>
          </ul>
          <div class="pill-row">
            <span class="pill small">Python</span>
            <span class="pill small">pandas</span>
            <span class="pill small">NumPy</span>
            <span class="pill small">scikit-learn</span>
            <span class="pill small">Matplotlib</span>
            <span class="pill small">Seaborn</span>
            <span class="pill small">Jupyter</span>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- Research -->
  <section id="research" class="section alt-section">
    <div class="container">
      <h2 class="section-title">Research & Publications</h2>
      <div class="card-grid">
        <article class="card">
          <div class="card-header">
            <h3>Gastric Carcinoma Detection using Hybrid Model based Transfer Learning</h3>
          </div>
          <p class="meta-text">
            International Journal of Scientific Research in Engineering and Management (IJSREM) • June 6, 2023
          </p>
          <p class="card-subtitle">
            Hybrid deep learning system for early detection of gastric carcinoma using medical imaging with transfer learning and
            CNN-based feature extraction.
          </p>
          <ul class="card-list">
            <li>Leveraged pre-trained CNNs and transfer learning for robust feature extraction from medical images.</li>
            <li>Applied advanced preprocessing and data augmentation to improve robustness and generalization.</li>
            <li>
              Evaluated the model using accuracy, AUC-ROC, and cross-validation, demonstrating strong predictive performance for
              early diagnosis.
            </li>
          </ul>
          <div class="pill-row">
            <span class="pill small">Transfer Learning</span>
            <span class="pill small">Medical Imaging</span>
            <span class="pill small">CNN</span>
            <span class="pill small">Hybrid Deep Learning</span>
          </div>
          <a
            href="https://ijsrem.com/download/gastric-carinoma-detection-using-hybrid-model-based-tl/"
            target="_blank"
            class="link-btn"
          >
            View Publication
          </a>
        </article>

        <article class="card">
          <div class="card-header">
            <h3>3D Face Modelling of Human Faces using GANs</h3>
          </div>
          <p class="meta-text">
            International Research Journal of Engineering and Technology (IRJET) • August 8, 2022
          </p>
          <p class="card-subtitle">
            GAN-based framework to generate realistic 3D human face models from limited 2D data, improving realism and identity preservation.
          </p>
          <ul class="card-list">
            <li>Combined CNN-based feature extraction with generative adversarial networks for 3D face reconstruction.</li>
            <li>
              Evaluated realism and structure with metrics like Inception Score, reconstruction error, and classification accuracy.
            </li>
            <li>Demonstrated the potential of generative AI in advanced computer vision applications.</li>
          </ul>
          <div class="pill-row">
            <span class="pill small">GANs</span>
            <span class="pill small">3D Modelling</span>
            <span class="pill small">Computer Vision</span>
            <span class="pill small">Generative AI</span>
          </div>
          <a
            href="https://www.irjet.net/archives/V9/i8/IRJET-V9I841.pdf"
            target="_blank"
            class="link-btn"
          >
            View Publication
          </a>
        </article>
      </div>
    </div>
  </section>

  <!-- Experience -->
  <section id="experience" class="section">
    <div class="container">
      <h2 class="section-title">Experience</h2>
      <div class="card-grid">
        <article class="card">
          <div class="card-header">
            <h3>Data Scientist</h3>
            <p class="meta-text">Inmar Intelligence • Oct 2023 – Jul 2024</p>
          </div>
          <ul class="card-list">
            <li>
              Worked on data-driven analytics projects using large-scale business and consumer datasets to support decision-making.
            </li>
            <li>
              Cleaned, preprocessed, and transformed structured data using Python (pandas, NumPy) and SQL to uncover trends and anomalies.
            </li>
            <li>
              Developed and evaluated machine learning models (classification and regression) to improve prediction accuracy for
              business use cases.
            </li>
            <li>
              Designed dashboards and visualizations (Power BI / Tableau / Matplotlib / Seaborn) to communicate insights to
              technical and non-technical stakeholders.
            </li>
            <li>
              Contributed to end-to-end analytics pipelines integrating ingestion, feature engineering, modeling, and evaluation.
            </li>
          </ul>
        </article>

        <article class="card">
          <div class="card-header">
            <h3>Data Analyst Intern</h3>
            <p class="meta-text">Evolv Technologies • May 2022 – Oct 2023</p>
          </div>
          <ul class="card-list">
            <li>
              Gathered, cleaned, and validated data from multiple business systems to create high-quality, analysis-ready datasets.
            </li>
            <li>
              Wrote and optimized SQL queries for data extraction, transformation, and aggregation to support reporting and analytics.
            </li>
            <li>
              Performed exploratory data analysis (EDA) and descriptive statistics to identify patterns, trends, and anomalies.
            </li>
            <li>
              Built interactive dashboards and reports in Power BI / Tableau to help stakeholders track KPIs and monitor performance.
            </li>
            <li>
              Collaborated with Data Scientists and Engineers to prepare feature-rich datasets for machine learning and advanced
              analytics projects.
            </li>
          </ul>
        </article>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="section alt-section">
    <div class="container contact-container">
      <div>
        <h2 class="section-title">Contact</h2>
        <p class="section-body">
          I’m open to opportunities in Data Science, Machine Learning, and Analytics.  
          Happy to discuss projects, research, or collaborations.
        </p>
      </div>
      <div class="contact-actions">
        <a href="mailto:srikarmanikonda4@gmail.com" class="btn primary-btn">Email Me</a>
        <a
          href="https://www.linkedin.com/in/srikar-manikonda"
          target="_blank"
          class="btn outline-btn"
        >
          LinkedIn
        </a>
        <a
          href="https://github.com/MSrikar7"
          target="_blank"
          class="btn ghost-btn"
        >
          GitHub
        </a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer">
    <div class="container footer-inner">
      <span>© 2025 Venkata Srikar Manikonda</span>
      <span class="footer-dot">•</span>
      <span>Built with HTML, CSS & JS</span>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
