# Ex01 Portfolio
## Date: 04.03.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
index.html

'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muralidharan M - AI Engineer Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="#hero" class="logo">MY PORTFOLIO</a>
        <ul>
            <li><a href="#hero">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="hero">
        <div class="hero-content">
            <h1>Muralidharan M</h1>
            <p>AI Engineer & Machine Learning Specialist</p>
            <a href="#projects" class="btn">Explore My Work</a>
        </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Muralidharan M, an AI Engineer with over 6 years of experience in designing and deploying cutting-edge machine learning models and AI systems. My passion lies in harnessing data and algorithms to solve complex problems and drive innovation.</p>
        <p>I specialize in deep learning, natural language processing, and computer vision, with a focus on building scalable AI solutions. From developing predictive models to optimizing neural networks, I thrive on transforming ideas into impactful technologies.</p>
        <p>When I'm not coding, you can find me researching the latest AI advancements, contributing to open-source ML projects, or enjoying a cup of tea while analyzing datasets.</p>
    </section>

    <section id="experience">
        <h2>My Experience</h2>
        <div class="experience-grid">
            <div class="experience-card">
                <h3>Senior AI Engineer</h3>
                <h4>AI Innovations Lab | 2022 - Present</h4>
                <p>Led a team in developing deep learning models for real-time image recognition, optimized large-scale ML pipelines, and deployed AI solutions for enterprise clients.</p>
            </div>
            <div class="experience-card">
                <h3>Machine Learning Engineer</h3>
                <h4>DataTech Solutions | 2019 - 2022</h4>
                <p>Built and trained NLP models for sentiment analysis and chatbot systems, integrated AI APIs, and collaborated with data scientists to enhance model accuracy.</p>
            </div>
            <div class="experience-card">
                <h3>Junior AI Developer</h3>
                <h4>TechStart Inc. | 2017 - 2019</h4>
                <p>Assisted in creating predictive models, performed data preprocessing, and learned advanced ML frameworks to support AI-driven projects.</p>
            </div>
        </div>
    </section>

    <section id="skills">
        <h2>My Skills</h2>
        <div class="skills-grid">
            <div class="skill-card">
                <h3>Machine Learning</h3>
                <p>Expertise in supervised and unsupervised learning, using frameworks like TensorFlow, PyTorch, and Scikit-learn.</p>
            </div>
            <div class="skill-card">
                <h3>Deep Learning</h3>
                <p>Building and optimizing neural networks for applications in computer vision and NLP using Keras and PyTorch.</p>
            </div>
            <div class="skill-card">
                <h3>Data Engineering</h3>
                <p>Designing data pipelines and preprocessing large datasets with tools like Apache Spark and Pandas.</p>
            </div>
            <div class="skill-card">
                <h3>Cloud AI</h3>
                <p>Deploying scalable AI models on cloud platforms like AWS, Google Cloud, and Azure.</p>
            </div>
        </div>
    </section>

    <section id="projects">
        <h2>My Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <img src="https://images.unsplash.com/photo-1534972195531-d756b9bfa9f2" alt="Image Recognition System">
                <h3>Image Recognition System</h3>
                <p>A deep learning-based system for real-time object detection and classification, achieving 95% accuracy on benchmark datasets.</p>
                <p class="tech-stack">Tech: Python, TensorFlow, OpenCV, AWS</p>
            </div>
            <div class="project-card">
                <img src="https://images.unsplash.com/photo-1534972195531-d756b9bfa9f2" alt="Chatbot Platform">
                <h3>Chatbot Platform</h3>
                <p>An NLP-powered chatbot for customer support, with sentiment analysis and multi-language capabilities, deployed for a retail client.</p>
                <p class="tech-stack">Tech: Python, PyTorch, spaCy, Google Cloud</p>
            </div>
            <div class="project-card">
                <img src="https://images.unsplash.com/photo-1534972195531-d756b9bfa9f2" alt="Predictive Analytics Tool">
                <h3>Predictive Analytics Tool</h3>
                <p>A machine learning tool for forecasting sales trends, using time-series analysis and ensemble models for high accuracy.</p>
                <p class="tech-stack">Tech: Python, Scikit-learn, Pandas, Azure</p>
            </div>
        </div>
    </section>

    <section id="testimonials">
        <h2>What Clients Say</h2>
        <div class="testimonial-grid">
            <div class="testimonial-card">
                <p>"Muralidharan’s AI expertise transformed our data analytics pipeline, delivering actionable insights with remarkable accuracy."</p>
                <h4>John Smith, CTO of DataCorp</h4>
            </div>
            <div class="testimonial-card">
                <p>"Working with Muralidharan was a game-changer. His chatbot solution elevated our customer experience significantly."</p>
                <h4>Emily Brown, Product Manager</h4>
            </div>
            <div class="testimonial-card">
                <p>"Muralidharan’s deep learning models exceeded our expectations, providing robust solutions for our vision-based product."</p>
                <h4>Michael Lee, Startup Founder</h4>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Get in Touch</h2>
        <p>I'm excited to collaborate on innovative AI projects or explore opportunities in machine learning and data science. I'm available for freelance work and open to full-time roles. Reach out via email or connect with me on social media.</p>
        <p><strong>Email:</strong> muralidharan.m@example.com</p>
        <p><strong>Phone:</strong> (123) 456-7890</p>
        <div class="social-links">
            <a href="https://linkedin.com" target="_blank">LinkedIn</a>
            <a href="https://github.com" target="_blank">GitHub</a>
            <a href="https://twitter.com" target="_blank">Twitter</a>
            <a href="https://kaggle.com" target="_blank">Kaggle</a>
        </div>
    </section>

    <footer>
        <p>© 2025 Muralidharan M. Designed & Built with Passion.</p>
    </footer>
</body>
</html>
'''


style.css
'''

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
    background: #f9f9f9;
}

/* Navigation */
nav {
    background: #1a2639;
    position: fixed;
    width: 100%;
    z-index: 1000;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 3rem;
}

.logo {
    color: #ecf0f1;
    font-size: 1.8rem;
    font-weight: bold;
    text-decoration: none;
    transition: color 0.3s ease;
}

.logo:hover {
    color: #e74c3c;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 2.5rem;
}

nav ul li a {
    color: #ecf0f1;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1rem;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #e74c3c;
}

/* Hero Section */
#hero {
    height: 100vh;
    background: linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.75)), url('https://images.unsplash.com/photo-1516321310764-9d961e7a6a85');
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #ecf0f1;
}

#hero .hero-content {
    max-width: 900px;
    padding: 2rem;
}

#hero h1 {
    font-size: 4rem;
    margin-bottom: 1.5rem;
    letter-spacing: 2px;
}

#hero p {
    font-size: 1.3rem;
    margin-bottom: 2.5rem;
    opacity: 0.9;
}

.btn {
    display: inline-block;
    padding: 1rem 2.5rem;
    background: #e74c3c;
    color: #fff;
    text-decoration: none;
    border-radius: 50px;
    font-weight: 600;
    transition: background 0.3s ease, transform 0.3s ease;
}

.btn:hover {
    background: #c0392b;
    transform: translateY(-3px);
}

/* About Section */
#about {
    padding: 6rem 2rem;
    max-width: 1200px;
    margin: 0 auto;
    text-align: center;
}

#about h2 {
    font-size: 2.8rem;
    margin-bottom: 2rem;
    color: #1a2639;
    position: relative;
}

#about h2::after {
    content: '';
    width: 80px;
    height: 4px;
    background: #e74c3c;
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
}

#about p {
    max-width: 800px;
    margin: 1rem auto;
    font-size: 1.1rem;
    color: #555;
}

/* Experience Section */
#experience {
    background: #fff;
    padding: 6rem 2rem;
}

#experience h2 {
    text-align: center;
    font-size: 2.8rem;
    margin-bottom: 3rem;
    color: #1a2639;
    position: relative;
}

#experience h2::after {
    content: '';
    width: 80px;
    height: 4px;
    background: #e74c3c;
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
}

.experience-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.experience-card {
    background: #f5f5f5;
    padding: 2rem;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.experience-card h3 {
    color: #1a2639;
    font-size: 1.5rem;
    margin-bottom: 0.5rem;
}

.experience-card h4 {
    color: #e74c3c;
    font-size: 1.2rem;
    margin-bottom: 1rem;
}

.experience-card p {
    color: #666;
}

/* Skills Section */
#skills {
    background: #fff;
    padding: 6rem 2rem;
}

#skills h2 {
    text-align: center;
    font-size: 2.8rem;
    margin-bottom: 3rem;
    color: #1a2639;
    position: relative;
}

#skills h2::after {
    content: '';
    width: 80px;
    height: 4px;
    background: #e74c3c;
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.skill-card {
    background: #f5f5f5;
    padding: 2rem;
    border-radius: 10px;
    text-align: center;
    transition: transform 0.3s ease;
}

.skill-card:hover {
    transform: translateY(-5px);
}

.skill-card h3 {
    color: #1a2639;
    margin-bottom: 1rem;
}

.skill-card p {
    color: #666;
}

/* Projects Section */
#projects {
    background: #f1f1f1;
    padding: 6rem 2rem;
}

#projects h2 {
    text-align: center;
    font-size: 2.8rem;
    margin-bottom: 3rem;
    color: #1a2639;
    position: relative;
}

#projects h2::after {
    content: '';
    width: 80px;
    height: 4px;
    background: #e74c3c;
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 2.5rem;
    max-width: 1200px;
    margin: 0 auto;
}

.project-card {
    background: #fff;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
}

.project-card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

.project-card h3 {
    padding: 1.5rem;
    color: #1a2639;
    font-size: 1.5rem;
}

.project-card p {
    padding: 0 1.5rem 1rem;
    color: #666;
}

.project-card .tech-stack {
    padding: 0 1.5rem 1.5rem;
    color: #e74c3c;
    font-size: 0.9rem;
}

/* Testimonials Section */
#testimonials {
    padding: 6rem 2rem;
    background: #fff;
}

#testimonials h2 {
    text-align: center;
    font-size: 2.8rem;
    margin-bottom: 3rem;
    color: #1a2639;
    position: relative;
}

#testimonials h2::after {
    content: '';
    width: 80px;
    height: 4px;
    background: #e74c3c;
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
}

.testimonial-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.testimonial-card {
    background: #f5f5f5;
    padding: 2rem;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.testimonial-card p {
    font-style: italic;
    color: #555;
    margin-bottom: 1rem;
}

.testimonial-card h4 {
    color: #1a2639;
    font-weight: 600;
}

/* Contact Section */
#contact {
    padding: 6rem 2rem;
    max-width: 900px;
    margin: 0 auto;
    text-align: center;
}

#contact h2 {
    font-size: 2.8rem;
    margin-bottom: 2rem;
    color: #1a2639;
    position: relative;
}

#contact h2::after {
    content: '';
    width: 80px;
    height: 4px;
    background: #e74c3c;
    position: absolute;
    bottom: -10px;
    left: 50%;
    transform: translateX(-50%);
}

#contact p {
    margin-bottom: 1.5rem;
    font-size: 1.1rem;
    color: #555;
}

.social-links {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-top: 2rem;
}

.social-links a {
    color: #e74c3c;
    text-decoration: none;
    font-size: 1.3rem;
    font-weight: 600;
    transition: color 0.3s ease;
}

.social-links a:hover {
    color: #c0392b;
}

/* Footer */
footer {
    background: #1a2639;
    color: #ecf0f1;
    text-align: center;
    padding: 2rem;
    font-size: 1rem;
}

/* Responsive Design */
@media (max-width: 768px) {
    #hero h1 {
        font-size: 2.8rem;
    }

    #hero p {
        font-size: 1.1rem;
    }

    nav {
        flex-direction: column;
        padding: 1rem;
        align-items: center;
    }

    .logo {
        margin-bottom: 1rem;
    }

    nav ul {
        justify-content: center;
    }

    nav ul li {
        margin: 0 1rem;
    }

    .project-grid {
        grid-template-columns: 1fr;
    }

    .skills-grid {
        grid-template-columns: 1fr;
    }

    .testimonial-grid {
        grid-template-columns: 1fr;
    }
}

@media (max-width: 480px) {
    #hero h1 {
        font-size: 2rem;
    }

    .btn {
        padding: 0.8rem 1.5rem;
    }

    .logo {
        font-size: 1.5rem;
    }

    nav ul li a {
        font-size: 0.9rem;
    }
}

'''


## OUTPUT

Home
![Screenshot 2025-04-25 180628](https://github.com/user-attachments/assets/dd107b57-726b-4a12-892f-41acb920e4b5)

About
![Screenshot 2025-04-25 180653](https://github.com/user-attachments/assets/db80d3bf-3cae-433b-a46b-3165dc8054e6)

Experience
![Screenshot 2025-04-25 180717](https://github.com/user-attachments/assets/f2a10209-0bdf-4203-90a5-24913aaeb5ce)

Skills
![Screenshot 2025-04-25 180726](https://github.com/user-attachments/assets/56791b58-fe48-40fe-9457-9dd9f043a0ae)

Projects
![Screenshot 2025-04-25 180735](https://github.com/user-attachments/assets/deb7d51f-67e8-4e94-90f5-d21aad1fdf31)

Review
![Screenshot 2025-04-25 180746](https://github.com/user-attachments/assets/9794972d-2933-4bd1-b26b-4fc7bd3bbb12)

Contacts
![Screenshot 2025-04-25 180801](https://github.com/user-attachments/assets/7ca2e6c2-5d7c-4650-8a06-3cf2f5967af3)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
