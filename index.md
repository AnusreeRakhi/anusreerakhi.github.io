---
layout: default
---

<div class="hero">
  <div class="hero-grid">
    <div>
      <img class="headshot" src="{{ 'Images/headshot_circle.png' | relative_url }}" alt="Headshot" />
    </div>

    <div>
      <h1 class="name">Anusree Mondal Rakhi</h1>
      <div class="role">Data Scientist</div>
      <div class="tagline">ML | LLMs | RAG | AI Agents | CV</div>

      <div class="meta">
        New York, NY<br />
        <a href="mailto:ar4636@columbia.edu">ar4636@columbia.edu</a> | <a href="tel:+16317208838">+1 (631) 720-8838</a><br />
        Work Authorization: Legal Permanent Resident
      </div>

      <div class="actions">
        <a class="btn" href="https://www.linkedin.com/in/anusreemondalrakhi/" target="_blank" rel="noopener">LinkedIn</a>
        <a class="btn" href="https://github.com/AnusreeRakhi" target="_blank" rel="noopener">GitHub</a>
        <a class="btn" href="{{ 'Resume.pdf' | relative_url }}" target="_blank" rel="noopener">Resume</a>
      </div>
    </div>
  </div>
</div>

<div class="section">
  <h2>Professional Summary</h2>
  Data Scientist and Columbia University graduate with 2 years of experience delivering end-to-end Machine Learning, Large Language Models, and Retrieval Augmented Generation solutions. Recently, I deepened my work in AI Agents through a Google course.
</div>

<div class="section">
  <h2>Key Highlights</h2>

  <div class="grid-3">
    <div class="stat">
      <strong>Cost Reduction</strong>
      <span>Reduced run cost from $46 to $2.30 per 10,000 URLs</span>
    </div>
    <div class="stat">
      <strong>Speed Improvement</strong>
      <span>Reduced multilingual processing from 4 weeks to 3 hours</span>
    </div>
    <div class="stat">
      <strong>Data Quality</strong>
      <span>Reduced inconsistencies by 34% across 120M+ records</span>
    </div>
  </div>
</div>

<div class="section">
  <h2>Technical Skills</h2>

  <div class="skills">
    <div class="skill-row"><div class="skill-label">Languages</div><div class="skill-value">Python, R, SQL</div></div>
    <div class="skill-row"><div class="skill-label">Machine Learning and Data</div><div class="skill-value">NumPy, pandas, SciPy, scikit-learn</div></div>
    <div class="skill-row"><div class="skill-label">Deep Learning</div><div class="skill-value">PyTorch, TensorFlow, Keras</div></div>
    <div class="skill-row"><div class="skill-label">NLP and Computer Vision</div><div class="skill-value">spaCy, NLTK, OpenCV</div></div>
    <div class="skill-row"><div class="skill-label">LLM Stack</div><div class="skill-value">LangChain, Hugging Face, FAISS, Embeddings, LLMs, RAG, AI Agents</div></div>
    <div class="skill-row"><div class="skill-label">Cloud</div><div class="skill-value">AWS (SageMaker, S3, Redshift, MLflow), GCP</div></div>
    <div class="skill-row"><div class="skill-label">MLOps</div><div class="skill-value">Automation, Retraining, Monitoring</div></div>
    <div class="skill-row"><div class="skill-label">Web Scraping</div><div class="skill-value">requests, BeautifulSoup, Selenium</div></div>
    <div class="skill-row"><div class="skill-label">Analytics</div><div class="skill-value">Hypothesis Testing, A/B Testing, Experimental Design, Evaluation Metrics, Data Mining</div></div>
    <div class="skill-row"><div class="skill-label">Visualization</div><div class="skill-value">Tableau, Power BI, Matplotlib, Seaborn, ggplot2</div></div>
    <div class="skill-row"><div class="skill-label">Data Quality</div><div class="skill-value">Validation, QA Checks</div></div>
    <div class="skill-row"><div class="skill-label">Tools</div><div class="skill-value">GitHub, Excel</div></div>
  </div>
</div>

<div class="section">
  <h2>Experience</h2>

  <div class="item">
    <p class="item-title">Mastercard | Applied AI Scientist</p>
    <div class="item-meta">New York, NY | Sep 2024 to Dec 2024</div>
    <ul>
      <li>Delivered a web-scraping and text-only ingestion pipeline for 10,000 URLs using BeautifulSoup batching with Selenium fallback</li>
      <li>Optimized multilingual translation by benchmarking 6 translators across 35 languages and productionizing the best performing translator, reducing end-to-end processing from 4 weeks to 3 hours</li>
      <li>Enabled cost-efficient website categorization using LLMs; evaluated keywords with synonym-aware Precision@3 against a human-annotated dataset, lowering run costs from $46 to $2.30 per 10,000 URLs and achieving approximately 16 to 20 minutes runtime with concurrency</li>
    </ul>
  </div>

  <div class="item">
    <p class="item-title">Columbia Climate School | Data Scientist</p>
    <div class="item-meta">New York, NY | Sep 2024 to Dec 2024</div>
    <ul>
      <li>Developed a Streamlit-based RAG application for environmental researchers and climate scientists to ingest multiple articles and reports and answer queries on scope of work, constraints, eligibility, and assumptions with source-cited responses</li>
      <li>Optimized document review by chunking and embedding documents and retrieving only the top relevant evidence per query, reducing OpenAI API token cost versus sending full reports and cutting turnaround time by 84%</li>
      <li>Optimized an existing CNN model by strengthening the convolution operation with stacked kernels, BatchNorm, Dropout, and EarlyStopping; increased accuracy by 8% and cut training time by about 15% without new data collection</li>
    </ul>
  </div>

  <div class="item">
    <p class="item-title">BlocPower | Data Scientist</p>
    <div class="item-meta">Brooklyn, NY | May 2024 to Aug 2024</div>
    <ul>
      <li>Led data validation on 120M+ records in Amazon Redshift (SQL), reduced data inconsistencies by 34% and improved data quality</li>
      <li>Developed and productionized supervised Machine Learning models (S3, Amazon SageMaker) to predict key building energy characteristics supporting decarbonization efforts</li>
      <li>Integrated model lifecycle into a production MLOps pipeline (MLflow) with a CI/CD workflow to automate retraining, validation, and deployment; enabled assessments that helped clients reduce energy waste by up to 80%</li>
      <li>Created performance monitoring reports for cross-functional teams (Engineering, Ops) providing actionable insights into critical business metrics</li>
    </ul>
  </div>

  <div class="item">
    <p class="item-title">Columbia Engineering | Machine Learning Research Assistant</p>
    <div class="item-meta">New York, NY | Sep 2023 to Apr 2024</div>
    <ul>
      <li>Reduced Teaching Assistants’ workload by 50% in high-enrollment courses by answering students’ queries through an LLM assistant</li>
      <li>Enabled fast, accurate semantic retrieval using a LangChain LLM plus RAG pipeline with embeddings and a vector database over an Excel knowledge base</li>
      <li>Improved answer reliability with Google PaLM using a strict context-only prompt and an “I don’t know” fallback, deployed via Streamlit with an admin re-index workflow</li>
      <li>Derived insights from 100,000 public health records across 30 years by building visualizations, linking demographic and social factors to lifestyle changes, and presenting findings through Tableau dashboards</li>
    </ul>
  </div>

  <div class="item">
    <p class="item-title">Gonit Shikkha Kendro | Data Science Instructor</p>
    <div class="item-meta">Dhaka, Bangladesh | Jun 2022 to Aug 2023</div>
    <ul>
      <li>Taught data preparation for ML, DL, and NLP models using Python, SQL, NumPy, pandas, Seaborn, scikit-learn, spaCy, NLTK</li>
      <li>Designed and led workshops on data storytelling, critical thinking, and strategy development for real-world data problems</li>
    </ul>
  </div>

  <div class="item">
    <p class="item-title">SRM Institute of Science and Technology | Deep Learning Research Assistant</p>
    <div class="item-meta">Chennai, India | Jun 2021 to May 2022</div>
    <ul>
      <li>Enhanced Mask-RCNN on satellite imagery by optimizing Backbone architecture (ResNet) and model hyperparameter tuning</li>
      <li>Achieved 82% object detection accuracy and published results with Springer</li>
    </ul>
  </div>
</div>

<div class="section">
  <h2>Education</h2>

  <div class="item">
    <p class="item-title">Columbia University</p>
    <div class="item-meta">New York, NY | Sep 2023 to Feb 2025</div>
    <div class="meta">Master of Science in Data Science</div>
    <div class="meta">Relevant Coursework: Exploratory Data Analysis and Visualization, Statistics, Machine Learning, Computer Vision, Deep Learning for NLP</div>
  </div>

  <div class="item">
    <p class="item-title">SRM Institute of Science and Technology</p>
    <div class="item-meta">Chennai, India | Jul 2018 to May 2022</div>
    <div class="meta">Bachelor of Technology in Computer Science and Engineering</div>
    <div class="meta">Relevant Coursework: Data Mining and Analysis, Database Management Systems, Design and Analysis of Algorithms</div>
  </div>
</div>
