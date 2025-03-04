<!-- App.vue -->
<template>
  <div class="app">
    <!-- Navigation Bar -->
    <nav class="navbar">
      <div class="container">
        <div :class="['logo', { 'hidden': isScrolled }]">
          <img src="/kk_faceLogo.png" alt="EXRS image" class="face-logo" @click="goToAbout">
        </div>
        <ul class="nav-links">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#education">Education</a></li>
          <li><a href="#skills">Skills</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="#activities">Activities</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
      <div class="container">
        <h1>Hello, I'm <span class="highlight">Kazybek</span></h1>
        <h2>BSc Computer Science Student @ University of Exeter</h2>
        <p>Currently first-year student with a strong foundation in Java and C++.</p>
        <p>Passionate about Computer Science & Engineering, Algorithms, and Humanoid Robotics and AI</p>
        <div class="cta-buttons">
          <a href="#projects" class="btn primary">View Projects</a>
          <a href="#contact" class="btn secondary">Contact Me</a>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about section">
      <div class="container">
        <h2 class="section-title">About Me</h2>
        <div class="about-content">
          <div class="about-image">
            <div class="image-placeholder"><img src="/kazy.jpeg" alt="profilePic" class="profilePic"></div>
          </div>
          <div class="about-text">
            <h3>Full name: <span class = "highlight">Kazybek Khairulla</span></h3>
            <p>I'm currently studying Computer Science at the University of Exeter. My interests lie primarily in Robotics Engineering and Artificial Intelligence with a focus in Autonomous Systems and Computer Vision.</p>
            <p>When I'm not coding, you can find me participating in hackathons, prototyping embedded systems hardware, or exploring the latest technologies in AI and Robotics.</p>
            <p>I'm actively seeking internship opportunities where I can apply my skills, learn from industry experts, and contribute to meaningful projects.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="education section">
      <div class="container">
        <h2 class="section-title">Education</h2>
        <div class="timeline">
          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <div class="timeline-content">
              <h3>Bachelor of Science in Computer Science</h3>
              <h4>University of Exeter</h4>
              <p class="timeline-date">2024 - 2027</p>
              <p>Relevant Coursework: Data Structures and Algorithms, Object-Oriented Programming, Machine Learning Fundamentals, Computational Mathematics, Computer Architecture, Discrete Math</p>
              <p>Upper Class Hons (pred)</p>
            </div>
          </div>
          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <div class="timeline-content">
              <h3>High School Diploma</h3>
              <h4>Nexus International School (Singapore)</h4>
              <p class="timeline-date">2020 - 2024</p>
              <p>IGCSE & International Baccalaureate Diploma</p>
              <p>IB HL: Computer Science, Economics, Business Management</p>
              <p>IB SL: AA Maths, English A, Chinese B (Mandarin)</p>
              <p>Activities: HackClub @Nexus Founder & Lead, co-Founder of 'NexWell' Wellbeing app</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills section">
      <div class="container">
        <h2 class="section-title">Skills</h2>
        <div class="skills-container">
          <div class="skills-category">
            <h3>Programming Languages</h3>
            <ul class="skills-list">
              <li>C/C++</li>
              <li>Java</li>
              <li>Python</li>
              <li>JavaScript</li>
            </ul>
          </div>
          <div class="skills-category">
            <h3>Mobile Development</h3>
            <ul class="skills-list">
              <li>Codename One</li>
              <li>Maven</li>
              <li>Gradle</li>
              <li>XCode & IntellIj IDEA</li>
            </ul>
          </div>
          <div class="skills-category">
            <h3>Tools & Technologies</h3>
            <ul class="skills-list">
              <li>Git & GitHub</li>
              <li>Linux</li>
              <li>Arduino + Raspberry Pi</li>
              <li>Docker</li>
              <li>MongoDB + Atlas</li>
              <li>SQL</li>
            </ul>
          </div>
          <div class="skills-category">
            <h3>Other Skills</h3>
            <ul class="skills-list">
              <li>Data Structures (Linked Lists, Queues, Stacks, Trees)</li>
              <li>Algorithms (Graph Theory)</li>
              <li>Machine Learning (t-SNE, PCA, UMAP using scikitlearn)</li>
              <li>Computer Architecture</li>
              <li>Software Development</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects section">
      <div class="container">
        <h2 class="section-title">Projects</h2>
        <div class="projects-grid">
          <div class="project-card">
            <div class="project-image"><img src="/nexwell.png" alt="nexwell" class="cardIcon"></div>
            <h3>Wellbeing Mobile App (Cross-platform)</h3>
            <p>Co-founder & Project Coordinator of 'NexWell'</p>
            <div class="project-tech">
              <span>Java</span>
              <span>Codename One</span>
              <span>Maven</span>
              <span>APIs</span>
              <span>iOS</span>
              <span>Android</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/emma-rei/nexus-mental-wellness" class="btn small" >View on GitHub</a>
              <a href="https://honeykidsasia.com/nexwell-nexus-learners/" class="btn small secondary">Featured article</a>
            </div>
          </div>
          <div class="project-card">
            <div class="project-image">    <img src="/kazcable.png" alt="KazCable Icon" class="cardIcon2"></div>
            <h3>kazCables DBMS Software</h3>
            <p>Built a DBMS Software for a client for managing company records using Java and MySQL.</p>
            <div class="project-tech">
              <span>Java</span>
              <span>Swing</span>
              <span>MySQL</span>
              <span>MailHog</span>
              <span>tempMail</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/Kazybekkh/KazCable-DBMS.git" class="btn small">View on GitHub</a>
            </div>
          </div>
          <div class="project-card">
            <div class="project-image">    <img src="/battleships.png" alt="Battleships Icon" class="cardIcon"></div>
            <h3>Battleships Game</h3>
            <p>Battleships game using Python and Flask</p>
            <div class="project-tech">
              <span>Python</span>
              <span>Flask</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/Kazybekkh/BattleshipsGame.git" class="btn small">View on GitHub</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Activities Section -->
    <section id="activities" class="activities section">
      <div class="container">
        <h2 class="section-title">Clubs & Activities</h2>
        <div class="activities-grid">
          <div class="activity-card">
            <h3>Robotics Society</h3>
            <p class="activity-role">Founder & President(25/26) Full-time</p>
            <p class="activity-date">2025 - Present</p>
            <p>Design, build, and program robotics projects. Host hands-on workshops, technical talks, and support students in robotics innovation.</p>
          </div>
          <div class="activity-card">
            <h3>Computer Science Society</h3>
            <p class="activity-role">Member</p>
            <p class="activity-date">2024 - Present</p>
            <p>Participated in hackathons between universities and competitive programming contests.</p>
          </div>
          <div class="activity-card">
            <h3>Google Developer Club</h3>
            <p class="activity-role">Active Member</p>
            <p class="activity-date">2024 - Present</p>
            <p>Led beginner friendly workshops in Python to introduce non-STEM students to Programming & CS.</p>
          </div>
          <div class="activity-card">
            <h3>Kazakh Society</h3>
            <p class="activity-role">Active Member</p>
            <p class="activity-date">2024 - Present</p>
            <p>Contribute to various events. Organized workshop quizzes to introduce students to kazakh culture.</p>
          </div>
          <div class="activity-card">
            <h3>HackClub@Nexus Lead (High School)</h3>
            <p class="activity-role">Founder & former-President</p>
            <p class="activity-date">2022-2024</p>
            <p>Organized weekly coding workshops, hackathons, and industry speaker events. Mentor high-school students in programming</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact section">
      <div class="container">
        <h2 class="section-title">Get In Touch</h2>
        <div class="contact-content">
          <div class="contact-info">
            <div class="contact-item">
              <h3>Email</h3>
              <p>khairullakazybek32@gmail.com</p>
            </div>
            <div class="contact-item">
              <h3>Location</h3>
              <p>Exeter, United Kingdom</p>
            </div>
            <div class="contact-item">
              <h3>Social</h3>
              <div class="social-links">
                <a href="https://github.com/Kazybekkh/" class="social-link">GitHub</a>
                <a href="https://www.linkedin.com/in/kazybek-khairulla-788058218/" class="social-link">LinkedIn</a>
                <a href="https://x.com/NightodevZ" class="social-link">Twitter</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
      <div class="container">
        <p>&copy; 2025 Kazybek. All Rights Reserved.</p>
        <p>Designed & Built with Vue.js</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    goToAbout() {
      window.location.href = '#about';
    }
  }
}
</script>
<style>
/* Base Styles */
:root {
  --primary-color: #2563eb;
  --secondary-color: #1e40af;
  --dark-color: #1e293b;
  --light-color: #f8fafc;
  --gray-color: #94a3b8;
  --success-color: #10b981;
  --warning-color: #f59e0b;
  --danger-color: #ef4444;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Inter', 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  color: var(--dark-color);
  background-color: var(--light-color);
}

a {
  text-decoration: none;
  color: inherit;
}

ul {
  list-style: none;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.section {
  padding: 5rem 0;
}

.section-title {
  font-size: 2.5rem;
  text-align: center;
  margin-bottom: 3rem;
  position: relative;
}

.section-title::after {
  content: '';
  position: absolute;
  width: 100px;
  height: 4px;
  background-color: var(--primary-color);
  bottom: -10px;
  left: 50%;
  transform: translateX(-50%);
}

.btn {
  display: inline-block;
  padding: 0.8rem 1.5rem;
  border-radius: 5px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
}

.btn.primary {
  background-color: var(--primary-color);
  color: white;
}
.face-logo {
  width: 100px; /* Adjust the width as needed */
  height: auto; /* Maintain aspect ratio */
  display: block;
  margin: 0 auto; /* Center the image */
}
.profilePic {
  width: 100%; /* Adjust the width as needed */
  border-radius: 10px;
}
.cardIcon {
  width: 200px; 
  height: auto; 
  display: block;
  margin: 0 auto; 
}
.cardIcon2 {
  width: 550px; 
  height: auto; 
  display: block;
  margin: 0 auto; 
  
}

.btn.secondary {
  background-color: transparent;
  color: var(--primary-color);
  border: 2px solid var(--primary-color);
}

.btn.small {
  padding: 0.5rem 1rem;
  font-size: 0.9rem;
}

.btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
}

.highlight {
  color: var(--primary-color);
}

/* Navigation Bar */
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  background-color: rgba(255, 255, 255, 0.95);
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  z-index: 100;
}

.navbar .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 2rem;
}

.logo {
  font-size: 1.8rem;
  font-weight: 700;
  color: var(--primary-color);
}

.nav-links {
  display: flex;
  gap: 1.5rem;
}

.nav-links a {
  font-weight: 500;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: var(--primary-color);
}

/* Hero Section */
.hero {
  height: 100vh;
  display: flex;
  align-items: center;
  background-color: var(--light-color);
  padding-top: 80px;
}

.hero h1 {
  font-size: 3.5rem;
  margin-bottom: 1rem;
}

.hero h2 {
  font-size: 2rem;
  color: var(--gray-color);
  margin-bottom: 1.5rem;
}

.hero p {
  font-size: 1.2rem;
  max-width: 600px;
  margin-bottom: 2rem;
}

.cta-buttons {
  display: flex;
  gap: 1rem;
}

/* About Section */
.about-content {
  display: flex;
  gap: 3rem;
  align-items: center;
  flex-wrap: wrap;
}

.about-image {
  flex: 1;
  max-width: 300px;
}

.image-placeholder {
  background-color: var(--gray-color);
  height: 300px;
  border-radius: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: 500;
}

.about-text {
  flex: 2;
}

.about-text p {
  margin-bottom: 1rem;
}

/* Education Section */
.timeline {
  position: relative;
  max-width: 800px;
  margin: 0 auto;
}

.timeline::before {
  content: '';
  position: absolute;
  width: 2px;
  background-color: var(--gray-color);
  top: 0;
  bottom: 0;
  left: 20px;
}

.timeline-item {
  position: relative;
  margin-bottom: 2rem;
  padding-left: 50px;
}

.timeline-dot {
  position: absolute;
  width: 16px;
  height: 16px;
  left: 13px;
  background-color: var(--primary-color);
  border-radius: 50%;
  z-index: 1;
}

.timeline-content {
  background-color: white;
  padding: 1.5rem;
  border-radius: 8px;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
}

.timeline-content h3 {
  margin-bottom: 0.5rem;
  color: var(--primary-color);
}

.timeline-content h4 {
  margin-bottom: 0.5rem;
  color: var(--dark-color);
}

.timeline-date {
  font-weight: 600;
  color: var(--gray-color);
  margin-bottom: 1rem;
}

/* Skills Section */
.skills-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
}

.skills-category h3 {
  margin-bottom: 1rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid var(--primary-color);
}

.skills-list li {
  margin-bottom: 0.5rem;
  padding-left: 1.5rem;
  position: relative;
}

.skills-list li::before {
  content: '→';
  position: absolute;
  left: 0;
  color: var(--primary-color);
}

/* Projects Section */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.project-card {
  background-color: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.project-image {
  height: 200px;
  background-color: var(--gray-color);
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-weight: 500;
}

.project-card h3 {
  margin: 1rem;
  color: var(--dark-color);
}

.project-card p {
  margin: 0 1rem 1rem;
  color: var(--gray-color);
}

.project-tech {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  padding: 0 1rem 1rem;
}

.project-tech span {
  background-color: rgba(37, 99, 235, 0.1);
  color: var(--primary-color);
  font-size: 0.8rem;
  padding: 0.3rem 0.6rem;
  border-radius: 20px;
}

.project-links {
  display: flex;
  gap: 0.5rem;
  padding: 0 1rem 1rem;
}

/* Activities Section */
.activities-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.activity-card {
  background-color: white;
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
}

.activity-card h3 {
  color: var(--primary-color);
  margin-bottom: 0.5rem;
}

.activity-role {
  font-weight: 600;
  margin-bottom: 0.3rem;
}

.activity-date {
  color: var(--gray-color);
  font-size: 0.9rem;
  margin-bottom: 1rem;
}

/* Contact Section */
.contact-content {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 3rem;
}

.contact-item {
  margin-bottom: 2rem;
}

.contact-item h3 {
  margin-bottom: 0.5rem;
  color: var(--primary-color);
}

.social-links {
  display: flex;
  gap: 1rem;
}

.social-link {
  padding: 0.5rem 1rem;
  background-color: rgba(37, 99, 235, 0.1);
  border-radius: 5px;
  transition: background-color 0.3s ease;
}

.social-link:hover {
  background-color: rgba(37, 99, 235, 0.2);
}

.form-group {
  margin-bottom: 1.5rem;
}

.form-group label {
  display: block;
  margin-bottom: 0.5rem;
  font-weight: 500;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 0.8rem;
  border: 1px solid var(--gray-color);
  border-radius: 5px;
  font-family: inherit;
}

.form-group input:focus,
.form-group textarea:focus {
  outline: none;
  border-color: var(--primary-color);
}

/* Footer */
.footer {
  background-color: var(--dark-color);
  color: white;
  padding: 2rem 0;
  text-align: center;
}

.footer p {
  margin-bottom: 0.5rem;
}

/* Responsive Design */
@media (max-width: 992px) {
  .about-content {
    flex-direction: column;
  }
  
  .contact-content {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 768px) {
  .navbar .logo{
    transition: opacity 0.3s ease;
  }
  .navbar .logo.hidden{
    opacity: 0;
  }
  .navbar .container {
    flex-direction: column;
    padding: 1rem;
  }
  
  .nav-links {
    margin-top: 1rem;
    flex-wrap: wrap;
    justify-content: center;
  }
  
  .hero h1 {
    font-size: 2.5rem;
  }
  
  .hero h2 {
    font-size: 1.5rem;
  }
  
  .section-title {
    font-size: 2rem;
  }
}

@media (max-width: 576px) {
  .container {
    padding: 0 1rem;
  }
  
  .skills-container {
    grid-template-columns: 1fr;
  }
  
  .projects-grid,
  .activities-grid {
    grid-template-columns: 1fr;
  }
}
</style>