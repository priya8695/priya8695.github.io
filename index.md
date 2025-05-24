---
layout: splash
title: "Priya Prabhakar"
excerpt: '<span style="color:rgb(83, 176, 156); font-family: Montserrat, sans-serif; font-weight: 500; text-shadow: 0 1px 2px rgba(0,0,0,0.3); font-size: 0.8em">AI Engineer | LLM & Computer Vision Specialist | Former ISRO Scientist</span>'
header:
  overlay_image: /assets/images/background.avif  # Use a tech/AI-themed image
  overlay_filter: rgba(0, 0, 0, 0.5)
  actions:
    - label: '<span style="font-family: Montserrat, sans-serif; font-weight: 500; color: white">Download Resume</span>'
      url: "/assets/files/cv.pdf"
---

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@500&display=swap" rel="stylesheet">


<!-- Navigation Anchors (Styled as Minimalist Buttons) -->
<div class="nav-anchors">
  <a href="#about" class="btn btn--primary">About</a>
  <a href="#skills" class="btn btn--primary">Skills</a>
  <a href="#projects" class="btn btn--primary">Projects</a>
  <a href="#papers" class="btn btn--primary">Papers</a>
  <a href="#timeline" class="btn btn--primary">Timeline</a>
  <a href="#interests" class="btn btn--primary">Interests</a>
  <a href="assets/files/thesis.pdf" class="btn btn--primary">Thesis</a>
</div>

<!-- About Section -->


<!-- About Section -->
<section id="about" class="section-container">
  <h2 class="section-title">About</h2>
  <div class="about-content">
    <div class="profile-side">
      <div class="profile-pic-container">
        <img src="/assets/images/priya.jpg" alt="Your Name" class="profile-pic">
      </div>
      <div class="contact-logos">
        <!-- Email -->
        <a href="mailto:priya8695@gmail.com" class="logo-link">
          <img src="/assets/images/gmail.png" alt="Email" class="contact-logo">
        </a>
        
        <!-- LinkedIn -->
        <a href="https://linkedin.com/in/priya-prabhakar" target="_blank" class="logo-link">
          <img src="/assets/images/linkedin.jpg" alt="LinkedIn" class="contact-logo">
        </a>
        
        <!-- GitHub -->
        <a href="https://github.com/priya8695" target="_blank" class="logo-link">
          <img src="/assets/images/github.webp" alt="GitHub" class="contact-logo">
        </a>
      </div>
    </div>
    <div class="about-text">
      <p style="font-size: 1rem; line-height: 1.8;">

        I’m Priya Prabhakar, an AI engineer and researcher with a diverse background spanning aerospace systems, medical imaging, and applied machine learning. I hold a Master’s degree in Computer Science with a specialization in Artificial Intelligence from Leiden University, and I bring over 4 years of experience as a Scientist/Engineer at ISRO.
        My work bridges foundational AI research with real-world applications. I'm passionate about building ethical, interpretable AI systems that are not only high-performing but also transparent and usable across domains. 

        Let’s connect and build something meaningful.
        Let’s build AI that cares—and works.
      </p>
    </div>
  </div>
</section>

<style>
/* About Section Styles */
.section-title {
  font-size: 2rem;
  font-weight: 700;
  color: rgb(26, 120, 109); /* mint green tone */
  margin-bottom: 0.5rem;
  text-align: center;
  max-width: 800px;
  margin: 0 auto 2rem;
}

.about-content {
  display: flex;
  gap: 3rem;
  align-items: flex-start;
  max-width: 1000px;
  margin: 0 auto;
  padding: 0 1.5rem;
  
}



.profile-side {
  display: flex;
  flex-direction: column;
  align-items: center;
  min-width: 200px;
  gap: 1.5rem;
}

.profile-pic-container {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  overflow: hidden;
  border: 3px solid rgb(26, 120, 109);
}

.profile-pic {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.contact-logos {
  display: flex;
  gap: 2rem;
  flex-wrap: wrap;
  justify-content: center;
}

.logo-link {
  display: inline-block;
  transition: transform 0.3s ease;
}

.contact-logo {
  width: 40px;
  height: 40px;
  object-fit: contain;
}

.logo-link:hover {
  transform: scale(1.1);
}

.about-text {
  flex: 1;
  font-size: 1.1rem;
  line-height: 1.6;
  color: #333;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .about-content {
    flex-direction: column;
    align-items: center;
    gap: 2rem;
  }
  
  .profile-side {
    margin-bottom: 1rem;
  }
  
  .about-text {
    text-align: center;
  }
  
  .contact-logos {
    gap: 1.5rem;
  }
  
  .contact-logo {
    width: 50px;
    height: 50px;
  }
}
</style>

<!-- Skills Section -->
<!-- Modern Animated Skills Section -->
<section id="skills" class="skills-modern">
  <div class="skills-header">
    <h2 class="skills-title">Skills</h2>
    <p class="skills-subtitle">Here's a snapshot of my technical toolkit and areas of expertise</p>
    <div class="skills-underline"></div>
  </div>

  <div class="skills-rows">
    <!-- Row 1 -->
    <div class="skill-row" data-aos="fade-up">
      <div class="skill-title">Programming Languages</div>
      <div class="skill-tags">
        <span class="skill-tag">Python</span>
        <span class="skill-tag">C</span>
        <span class="skill-tag">C++</span>
        <span class="skill-tag">Java</span>
      </div>
    </div>

    <!-- Row 2 -->
    <div class="skill-row" data-aos="fade-up" data-aos-delay="100">
      <div class="skill-title">ML Frameworks</div>
      <div class="skill-tags">
        <span class="skill-tag">PyTorch</span>
        <span class="skill-tag">TensorFlow</span>
        <span class="skill-tag">Keras</span>
        <span class="skill-tag">OpenCV</span>
        <span class="skill-tag">MONAI</span>
      </div>
    </div>

    <!-- Row 3 -->
    <div class="skill-row" data-aos="fade-up" data-aos-delay="200">
      <div class="skill-title">Tools & Platforms</div>
      <div class="skill-tags">
        <span class="skill-tag">Docker</span>
        <span class="skill-tag">Kubernetes</span>
        <span class="skill-tag">AWS</span>
        <span class="skill-tag">Azure</span>
        <span class="skill-tag">Git</span>
      </div>
    </div>

    <!-- Row 4 -->
    <div class="skill-row" data-aos="fade-up" data-aos-delay="300">
      <div class="skill-title">Specializations</div>
      <div class="skill-tags">
        <span class="skill-tag">Deep Learning</span>
        <span class="skill-tag">NLP</span>
        <span class="skill-tag">LLMs</span>
        <span class="skill-tag">Computer Vision</span>
        <span class="skill-tag">MLOps</span>
      </div>
    </div>

    <!-- Row 5 -->
    <div class="skill-row" data-aos="fade-up" data-aos-delay="400">
      <div class="skill-title">Soft Skills</div>
      <div class="skill-tags">
        <span class="skill-tag">Problem Solving</span>
        <span class="skill-tag">Communication</span>
        <span class="skill-tag">Teamwork</span>
        <span class="skill-tag">Scientific Writing</span>
      </div>
    </div>
  </div>
</section>

<style>
/* Modern Skills Section Styles */

.skills-modern {
  padding: 4rem 1rem;
  margin-bottom: 2rem; /* Adds space after section */
}



.skills-title {
  font-size: 2rem;
  font-weight: 700;
  color: #00796b; /* mint green tone */
  text-align: center;
  max-width: 800px;
  margin: 0 auto 2rem;
}

.skills-subtitle {
  font-size: 1rem;
  color: #6b7280;
  max-width: 600px;
  margin: 0 auto;
}



.skills-rows {
  max-width: 900px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.skill-row {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  gap: 1rem;
}

.skill-title {
  flex: 0 0 200px;
  font-weight: 600;
  font-size: 1.1rem;
  color: #2e353f;
}

.skill-tags {
  flex: 1;
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.skill-tag {
  background: #e0f2f1;
  color: #00796b;
  padding: 0.4rem 0.9rem;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 500;
  transition: all 0.2s ease;
}

.skill-tag:hover {
  background: #00796b;
  color: #ffffff;
  transform: scale(1.05);
}

@media (max-width: 768px) {
  .skill-row {
    flex-direction: column;
  }

  .skill-title {
    margin-bottom: 2 rem;
  }
}

</style>




<!-- Projects Section -->
<section id="projects" class="section-container">
  <div class="section-header">
    <h2 class="section-title">Featured Projects</h2>
    <p class="section-subtitle">Selected AI implementations with measurable impact</p>
    <div class="section-divider"></div>
  </div>

  <div class="project-grid">
    <!-- Project 1 -->
    <div class="project-card">
      <div class="project-header">
        <h3>Aorta Segmentation System</h3>
        <span class="project-badge">Medical AI</span>
      </div>
      <p class="project-description">
        Developed UNet/Transformer hybrid model achieving 94.6% Dice score for 
        aorta segmentation in DICOM CT scans, enabling AR surgical planning.
      </p>
      <div class="project-tech">
        <span>PyTorch</span>
        <span>MONAI</span>
        <span>3D Slicer</span>
      </div>
      <a href="https://github.com/priya8695/Masters-Thesis" target="_blank" rel="noopener noreferrer" class="project-link">View Details →</a>
    </div>

    <!-- Project 2 -->
    <div class="project-card">
      <div class="project-header">
        <h3> Breast cancer detection and its classification as Benign or Malignant</h3>
        <span class="project-badge">Medical AI</span>
      </div>
      <p class="project-description">
        Reduced ISRO launch vehicle telemetry analysis time by 45% through 
        automated anomaly detection system using time-series forecasting.
      </p>
      <div class="project-tech">
        <span>LSTM</span>
        <span>Prophet</span>
        <span>MLOps</span>
      </div>
      <a href="https://github.com/priya8695/breast_cancer_classification" class="project-link">View Details →</a>
    </div>


  <!-- Project 3 -->
    <div class="project-card">
      <div class="project-header">
        <h3>AQI forecasting </h3>
        <span class="project-badge">Time series forecasting</span>
      </div>
      <p class="project-description">
        Developed an advanced LSTM+CNN model with attention mechanism for Air Quality Index prediction across Indian cities. Our model outperforms state-of-the-art approaches in accuracy and robustness, providing reliable predictions to help mitigate pollution exposure.
      </p>
      <div class="project-tech">
        <span>LSTM</span>
        <span>CNN</span>
        <span>Attention Mechanism</span>
        <span>TensorFlow</span>
        <span>Time Series</span>
      </div>
      <a href="https://github.com/priya8695/air-index-quality-forecasting" target="_blank" rel="noopener noreferrer" class="project-link">View Details →</a>
    </div>
 
  
 

 <!-- Project 4 -->
    <div class="project-card">
      <div class="project-header">
        <h3> Classifying fake audios  </h3>
        <span class="project-badge">Audio analysis</span>
      </div>
      <p class="project-description">
        Developed a CNN-LSTM hybrid model for detecting AI-generated speech using the ASVspoof2019 dataset. The proposed system achieves state-of-the-art accuracy in classifying audio as 'bonafide' (human) or 'spoof' (AI-generated), combining time-domain analysis with advanced feature extraction. Includes a Streamlit web interface for real-time audio classification.
      </p>
      <div class="project-tech">
        <span>LSTM</span>
        <span>CNN</span>
        <span>Streamlit</span>
        <span>PyTorch</span>
      </div>
      <a href="https://github.com/priya8695/Classifying_fake_audios" target="_blank" rel="noopener noreferrer" class="project-link">View Details →</a>
    </div>
  </div>
  
  <div class="text-center">
    <a href="https://github.com/priya8695" class="btn btn--primary" target="_blank">
      View All Projects on GitHub
    </a>
  </div>


<style>   

.text-center{
  gap: 2rem;
  margin-top: 2rem;
  margin-bottom: 2rem;

}    

.project-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  background: white;
  border-radius: 12px;
  padding: 1.5rem;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
  transition: transform 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
}

.project-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 2rem;
}

.project-badge {
  background: #e6fffa;
  color: #38b2ac;
  padding: 0.25rem 0.75rem;
  border-radius: 9999px;
  font-size: 0.8rem;
  font-weight: 600;
}

.project-tech {
  display: flex;
  gap: 0.5rem;
  margin: 1.5rem 0;
  flex-wrap: wrap;
}

.project-tech span {
  background: #f0f5ff;
  color: #5a67d8;
  padding: 0.25rem 0.75rem;
  border-radius: 9999px;
  font-size: 0.8rem;
}

.project-link {
  color: #4299e1;
  font-weight: 600;
  display: inline-flex;
  align-items: center;
  gap: 0.25rem;
}


</style>

<!-- Papers Section -->
<section id="papers" class="section-container">
  <h2 class="section-title">Publications</h2>
  <div class="publications-list">
    <div class="publication-item">
      <h3 class="publication-title">
        <a href="/assets/files/ncaqr_paper.pdf">"Towards Telemetry Format Verification of Launch Vehicle"</a>
      </h3>
      <div class="publication-meta">
        <span class="publication-journal">Journal for Aerospace Quality and Reliability</span>
        <span class="publication-year">2019</span>
      </div>
      <p class="publication-abstract">
        Proposed ML-based framework for automated verification of launch vehicle telemetry 
        data formats, reducing manual validation time by 30%.
      </p>
    </div>
    
    <div class="publication-item">
      <h3 class="publication-title">
        <a href="/assets/files/dsaa.pdf">"Towards Automated Breast Mass Classification
using Deep Learning Framework"</a>
      </h3>
      <div class="publication-meta">
        <span class="publication-journal">IEEE DSAA</span>
        <span class="publication-year">2019</span>
      </div>
      <p class="publication-abstract">
        Developed CAD system achieving 92.4% accuracy in mammogram classification using 
        custom CNN architecture with attention mechanisms.
      </p>
    </div>
  </div>
</section>

<!-- Timeline with Logo Circles Only -->
<section id="timeline" class="container py-5">
  <div class="text-center mb-5">
    <h2 class="timeline-heading">Professional Journey</h2>
    <p class="timeline-subheading">From ISRO to AI Research</p>
  </div>

  <div class="timeline-elegant">
    <!-- Vertical Line -->
    <div class="timeline-axis"></div>

    <!-- Entry 1 -->
    <div class="timeline-entry left">
      <div class="timeline-logo-container">
        <img src="/assets/images/freelance.png" alt="Freelance" class="timeline-logo">
      </div>
      <div class="timeline-content">
        <div class="timeline-date">2023 - Present</div>
        <h3 class="timeline-title">Freelance AI Engineer</h3>
        <div class="timeline-description">
          <ul>
            <li>Fine-tuned LLMs using RLHF techniques</li>
            <li>Developed real-time object detection systems</li>
            <li>Built custom AI applications with PyTorch/TensorFlow</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Entry 2 -->
    <div class="timeline-entry right">
      <div class="timeline-logo-container">
        <img src="/assets/images/medicalvr.png" alt="Surgical Reality" class="timeline-logo">
      </div>
      <div class="timeline-content">
        <div class="timeline-date">2022 - 2023</div>
        <h3 class="timeline-title">AI Engineer Intern</h3>
        <p class="timeline-location">Surgical Reality, Netherlands</p>
        <div class="timeline-description">
          <ul>
            <li>Achieved 94.6% Dice score for aorta segmentation</li>
            <li>Developed UNet/Transformer models for DICOM CT</li>
            <li>Created AR visualization for surgical planning</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Entry 3 -->
    <div class="timeline-entry left">
      <div class="timeline-logo-container">
        <img src="/assets/images/leiden.png" alt="Leiden University" class="timeline-logo">
      </div>
      <div class="timeline-content">
        <div class="timeline-date">2022 - 2024</div>
        <h3 class="timeline-title">MSc Computer Science (Specialisation in AI)</h3>
        <p class="timeline-location">Leiden University</p>
        
        <div class="timeline-description">
          <ul>
            <li>Thesis: "Aorta Segmentation & Geometric Analysis"</li>
            <li>Courses: RL, NLP, Medical Imaging, Evolutionary Algorithms</li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Entry 4 -->
    <div class="timeline-entry right">
      <div class="timeline-logo-container">
        <img src="/assets/images/isro.png" alt="ISRO" class="timeline-logo">
      </div>
      <div class="timeline-content">
        <div class="timeline-date">2017 - 2022</div>
        <h3 class="timeline-title">Scientist/Engineer</h3>
        <p class="timeline-location">ISRO, India</p>
        <div class="timeline-description">
          <ul>
            
            <li>Reduced telemetry errors by 30% using MLOps</li>
            <li>Automated data analysis (45% time reduction)</li>
            <li>Contributed to Chandrayaan mission analytics</li>
         
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
/* Timeline with Circular Logo Containers Only */
.timeline-elegant {
  position: relative;
  max-width: 1000px;
  margin: 0 auto;
  padding: 2rem 0;
}

.timeline-axis {
  position: absolute;
  left: 50%;
  top: 0;
  bottom: 0;
  width: 2px;
  background: #e0e0e0;
  transform: translateX(-50%);
}

.timeline-entry {
  position: relative;
  width: 100%;
  margin-bottom: 3rem;
}

.timeline-logo-container {
  position: absolute;
  left: 50%;
  top: 0;
  width: 110px;
  height: 110px;
  transform: translateX(-50%);
  background: white;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 0 0 4px white, 0 2px 10px rgba(0,0,0,0.1);
  border: 2px solid #00ffc8;
  z-index: 1;
}

.timeline-logo {
  width: 80%;
  height: 80%;
  object-fit: contain;
}

.timeline-content {
  width: 45%;
  padding: 0;
}

.timeline-entry.left .timeline-content {
  margin-right: auto;
  
  padding-right: 30px;
}

.timeline-entry.right .timeline-content {
  margin-left: auto;
 
  padding-left: 30px;
}

/* Typography (unchanged from your original) */
.timeline-heading {
  font-size: 2rem;
  font-weight: 700;
  color: #037d6f;
  margin: 0 auto 2rem;
}

.timeline-subheading {
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 300;
  font-size: 1.25rem;
  color: #7f8c8d;
  letter-spacing: 0.5px;
}

.timeline-title {
  font-family: 'Playfair Display', serif;
  font-weight: 600;
  font-size: 1.5rem;
  color: #2c3e50;
  margin-bottom: 0.5rem;
}

.timeline-date {
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 600;
  font-size: 0.9rem;
  color: #00796b;
  text-transform: uppercase;
  letter-spacing: 1px;
  margin-bottom: 0.5rem;
}

.timeline-location {
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 400;
  font-style: italic;
  font-size: 1rem;
  color: #7f8c8d;
  margin-bottom: 1rem;
}

.timeline-description {
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: 400;
  font-size: 1.05rem;
  line-height: 1.6;
  color: #34495e;
  text-align: justify;
}

.timeline-description ul {
  padding-left: 1.25rem;
}

.timeline-description li {
  margin-bottom: 0.5rem;
  position: relative;
}

.timeline-description li::before {
  content: "•";
  color: #00796b;
  font-weight: bold;
  display: inline-block;
  width: 1em;
  margin-left: -1em;
}

/* Mobile Responsive */
@media (max-width: 768px) {
  .timeline-axis,
  .timeline-logo-container {
    left: 20px;
  }
  
  .timeline-content {
    width: 80%;
    margin-left: 60px !important;
    text-align: left !important;
    padding-left: 0 !important;
    padding-right: 0 !important;
  }
}
</style>

<style>
  /* Custom CSS for navigation anchors */
  .nav-anchors {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    justify-content: center;
    margin: 2rem 0;
  }
  
  /* Skills grid */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 2rem;
  }
  
  
</style>

<!-- Minimalist Interests Section -->
<section id="interests" class="section-container">
  <h2 class="section-title">Beyond Code</h2>
  <div class="interests-flow">
    <!-- Photography -->
    <div class="interest-item">
      <div class="interest-icon">
        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/>
          <circle cx="12" cy="13" r="4"/>
        </svg>
      </div>
      <div class="interest-content">
        <h3>Photography</h3>
        <p>Capturing fleeting moments where light and shadow tell their own stories</p>
      </div>
    </div>

    <!-- Travel -->
    <div class="interest-item">
      <div class="interest-icon">
        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/>
          <circle cx="12" cy="10" r="3"/>
        </svg>
      </div>
      <div class="interest-content">
        <h3>Wandering</h3>
        <p>Collecting sunsets, mountain air, and unexpected conversations</p>
      </div>
    </div>

    <!-- Adventure -->
    <div class="interest-item">
      <div class="interest-icon">
        <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <path d="M18 8h1a4 4 0 0 1 0 8h-1"></path>
          <path d="M12 8h1a4 4 0 0 1 0 8h-1"></path>
          <path d="M6 8H7a4 4 0 0 1 0 8H6"></path>
          <line x1="6" y1="12" x2="7" y2="12"></line>
          <line x1="12" y1="12" x2="13" y2="12"></line>
        </svg>
      </div>
      <div class="interest-content">
        <h3>Adventure</h3>
        <p>Chasing that fleeting moment when fear turns into exhilaration</p>
      </div>
    </div>
  </div>
</section>

<style>
/* Minimalist Interests Design */


.interests-flow {
  display: flex;
  flex-direction: column;
  gap: 2.5rem;
  max-width: 600px;
  margin: 2rem auto;
  padding: 0 1rem;
}

.interest-item {
  display: flex;
  align-items: flex-start;
  gap: 1.5rem;
  position: relative;
  padding-left: 1rem;
}

.interest-item:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 2px;
  background: linear-gradient(to bottom, 
    transparent 0%, 
    rgba(83, 176, 156, 0.5) 30%, 
    rgba(83, 176, 156, 0.5) 70%, 
    transparent 100%);
}

.interest-icon {
  color: rgb(83, 176, 156);
  margin-top: 0.25rem;
}

.interest-content h3 {
  font-family: 'Playfair Display', serif;
  font-weight: 600;
  color: #2c3e50;
  margin-bottom: 0.5rem;
  font-size: 1.25rem;
}

.interest-content p {
  font-family: 'Crimson Pro', serif;
  font-weight: 400;
  color: #7f8c8d;
  line-height: 1.7;
  font-size: 1rem;
  margin: 0;
}

/* Animation */
.interest-item {
  transition: transform 0.3s ease;
}

.interest-item:hover {
  transform: translateX(8px);
}

/* Mobile Responsive */
@media (max-width: 768px) {
  .interest-item {
    gap: 1rem;
  }
}
</style>