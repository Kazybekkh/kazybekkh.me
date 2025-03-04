<!-- App.vue -->
<template>
  <div class="app">
    <!-- Navigation Bar -->
    <nav class="navbar">
      <div class="container">
        <div class="logo">KK</div>
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
        <h2>Computer Science Student</h2>
        <p>Passionate about software development, algorithms, and problem-solving</p>
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
            <div class="image-placeholder">Profile Image</div>
          </div>
          <div class="about-text">
            <p>I'm a Computer Science student with a passion for developing innovative solutions to complex problems. My academic journey has equipped me with strong foundations in algorithms, data structures, and software engineering principles.</p>
            <p>When I'm not coding, you can find me participating in hackathons, contributing to open-source projects, or exploring the latest technologies in AI and web development.</p>
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
              <h4>University Name</h4>
              <p class="timeline-date">2022 - Present</p>
              <p>Relevant Coursework: Data Structures and Algorithms, Object-Oriented Programming, Database Systems, Computer Networks, Operating Systems, Software Engineering</p>
              <p>GPA: 3.8/4.0</p>
            </div>
          </div>
          <div class="timeline-item">
            <div class="timeline-dot"></div>
            <div class="timeline-content">
              <h3>High School Diploma</h3>
              <h4>High School Name</h4>
              <p class="timeline-date">2018 - 2022</p>
              <p>Advanced Placement in Mathematics and Computer Science</p>
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
              <li>Python</li>
              <li>Java</li>
              <li>C++</li>
              <li>JavaScript</li>
              <li>TypeScript</li>
            </ul>
          </div>
          <div class="skills-category">
            <h3>Web Development</h3>
            <ul class="skills-list">
              <li>HTML/CSS</li>
              <li>Vue.js</li>
              <li>React</li>
              <li>Node.js</li>
              <li>Express</li>
            </ul>
          </div>
          <div class="skills-category">
            <h3>Tools & Technologies</h3>
            <ul class="skills-list">
              <li>Git & GitHub</li>
              <li>Docker</li>
              <li>AWS</li>
              <li>MongoDB</li>
              <li>SQL</li>
            </ul>
          </div>
          <div class="skills-category">
            <h3>Other Skills</h3>
            <ul class="skills-list">
              <li>Data Structures</li>
              <li>Algorithms</li>
              <li>Machine Learning</li>
              <li>Agile Development</li>
              <li>Problem Solving</li>
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
            <div class="project-image">Project 1 Image</div>
            <h3>Algorithmic Trading Bot</h3>
            <p>Developed a Python-based trading bot that uses machine learning algorithms to predict stock market trends and execute trades automatically.</p>
            <div class="project-tech">
              <span>Python</span>
              <span>TensorFlow</span>
              <span>APIs</span>
            </div>
            <div class="project-links">
              <a href="#" class="btn small">Demo</a>
              <a href="#" class="btn small secondary">GitHub</a>
            </div>
          </div>
          <div class="project-card">
            <div class="project-image">Project 2 Image</div>
            <h3>Campus Navigation App</h3>
            <p>Created a mobile application to help students navigate campus, find classrooms, and manage their course schedules efficiently.</p>
            <div class="project-tech">
              <span>React Native</span>
              <span>Firebase</span>
              <span>Google Maps API</span>
            </div>
            <div class="project-links">
              <a href="#" class="btn small">Demo</a>
              <a href="#" class="btn small secondary">GitHub</a>
            </div>
          </div>
          <div class="project-card">
            <div class="project-image">Project 3 Image</div>
            <h3>Course Management System</h3>
            <p>Built a full-stack web application for course management, allowing professors to create assignments and students to submit their work.</p>
            <div class="project-tech">
              <span>Vue.js</span>
              <span>Node.js</span>
              <span>MongoDB</span>
            </div>
            <div class="project-links">
              <a href="#" class="btn small">Demo</a>
              <a href="#" class="btn small secondary">GitHub</a>
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
            <h3>Computer Science Society</h3>
            <p class="activity-role">Vice President</p>
            <p class="activity-date">2023 - Present</p>
            <p>Organize weekly coding workshops, hackathons, and industry speaker events. Mentor junior students in programming and career development.</p>
          </div>
          <div class="activity-card">
            <h3>Competitive Programming Team</h3>
            <p class="activity-role">Team Member</p>
            <p class="activity-date">2022 - Present</p>
            <p>Participate in regional and national competitive programming contests. Achieved top 10 ranking in the 2023 Regional Collegiate Programming Contest.</p>
          </div>
          <div class="activity-card">
            <h3>Open Source Contributors Club</h3>
            <p class="activity-role">Active Member</p>
            <p class="activity-date">2023 - Present</p>
            <p>Contribute to various open source projects. Organized workshops to introduce students to open source contribution.</p>
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
              <p>yourname@email.com</p>
            </div>
            <div class="contact-item">
              <h3>Location</h3>
              <p>City, Country</p>
            </div>
            <div class="contact-item">
              <h3>Social</h3>
              <div class="social-links">
                <a href="#" class="social-link">GitHub</a>
                <a href="#" class="social-link">LinkedIn</a>
                <a href="#" class="social-link">Twitter</a>
              </div>
            </div>
          </div>
          <div class="contact-form">
            <form>
              <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
              </div>
              <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
              </div>
              <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>
              </div>
              <button type="submit" class="btn primary">Send Message</button>
            </form>
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
  data() {
    return {
      // Data can be added here if needed for dynamic content
    }
  },
  methods: {
    // Methods can be added here
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
}

.about-image {
  flex: 1;
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