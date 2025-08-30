

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>## Hi there 👋</title>
    <style>
        :root {
            --primary-color: #2d4cc8;
            --secondary-color: #6e5494;
            --accent-color: #00adb5;
            --text-color: #333;
            --light-bg: #f5f5f5;
            --dark-bg: #24292e;
            --card-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--light-bg);
            color: var(--text-color);
            line-height: 1.6;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .container {
            background-color: white;
            border-radius: 10px;
            box-shadow: var(--card-shadow);
            padding: 30px;
            margin-bottom: 20px;
        }
        
        header {
            text-align: center;
            padding: 30px 0;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            border-radius: 10px 10px 0 0;
            margin-bottom: 20px;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        h2 {
            color: var(--primary-color);
            margin: 20px 0 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid var(--light-bg);
        }
        
        h3 {
            color: var(--secondary-color);
            margin: 15px 0 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 20px;
        }
        
        .badges {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }
        
        .badge {
            display: inline-block;
            background-color: var(--dark-bg);
            color: white;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .intro {
            display: flex;
            align-items: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        
        .profile-img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            object-fit: cover;
            border: 5px solid white;
            box-shadow: var(--card-shadow);
        }
        
        .intro-text {
            flex: 1;
            min-width: 300px;
        }
        
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .skill-category {
            background-color: var(--light-bg);
            padding: 20px;
            border-radius: 8px;
        }
        
        .skill {
            margin-bottom: 15px;
        }
        
        .skill-name {
            display: flex;
            justify-content: space-between;
            margin-bottom: 5px;
        }
        
        .progress-bar {
            height: 10px;
            background-color: #e0e0e0;
            border-radius: 5px;
            overflow: hidden;
        }
        
        .progress {
            height: 100%;
            background-color: var(--accent-color);
            border-radius: 5px;
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .project-card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: var(--card-shadow);
            transition: transform 0.3s ease;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
        }
        
        .project-img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        
        .project-content {
            padding: 20px;
        }
        
        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin: 10px 0;
        }
        
        .tech-tag {
            background-color: var(--light-bg);
            padding: 3px 8px;
            border-radius: 4px;
            font-size: 0.8rem;
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            text-align: center;
            margin: 30px 0;
        }
        
        .stat-card {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 20px;
            border-radius: 8px;
        }
        
        .stat-number {
            font-size: 2rem;
            font-weight: bold;
            margin-bottom: 5px;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        
        .contact-btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: var(--primary-color);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        
        .contact-btn:hover {
            background-color: var(--secondary-color);
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #777;
        }
        
        @media (max-width: 768px) {
            .intro {
                justify-content: center;
                text-align: center;
            }
            
            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p class="tagline">Full Stack Software Engineer</p>
        <div class="badges">
            <span class="badge">JavaScript</span>
            <span class="badge">TypeScript</span>
            <span class="badge">React</span>
            <span class="badge">Node.js</span>
            <span class="badge">Python</span>
            <span class="badge">AWS</span>
        </div>
    </header>
    
    <div class="container">
        <section class="intro">
            <img src="https://via.placeholder.com/200" alt="Profile Picture" class="profile-img">
            <div class="intro-text">
                <h2>Hello World! 👋</h2>
                <p>I'm a passionate Full Stack Software Engineer with expertise in building scalable web applications and digital solutions. I enjoy turning complex problems into simple, beautiful and intuitive solutions.</p>
                <p>With experience in both front-end and back-end technologies, I bring ideas to life through clean, efficient code and thoughtful user experiences.</p>
                <p>When I'm not coding, you can find me contributing to open source projects, learning new technologies, or sharing knowledge with the developer community.</p>
            </div>
        </section>
    </div>
    
    <div class="container">
        <h2>Skills & Technologies</h2>
        <div class="skills-container">
            <div class="skill-category">
                <h3>Frontend Development</h3>
                <div class="skill">
                    <div class="skill-name">
                        <span>React</span>
                        <span>90%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 90%;"></div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">
                        <span>TypeScript</span>
                        <span>85%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 85%;"></div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">
                        <span>Vue.js</span>
                        <span>75%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 75%;"></div>
                    </div>
                </div>
            </div>
            
            <div class="skill-category">
                <h3>Backend Development</h3>
                <div class="skill">
                    <div class="skill-name">
                        <span>Node.js</span>
                        <span>88%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 88%;"></div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">
                        <span>Python/Django</span>
                        <span>80%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 80%;"></div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">
                        <span>PostgreSQL</span>
                        <span>85%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 85%;"></div>
                    </div>
                </div>
            </div>
            
            <div class="skill-category">
                <h3>Other Technologies</h3>
                <div class="skill">
                    <div class="skill-name">
                        <span>AWS</span>
                        <span>75%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 75%;"></div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">
                        <span>Docker</span>
                        <span>70%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 70%;"></div>
                    </div>
                </div>
                <div class="skill">
                    <div class="skill-name">
                        <span>CI/CD</span>
                        <span>80%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress" style="width: 80%;"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
    <div class="container">
        <h2>Featured Projects</h2>
        <div class="projects">
            <div class="project-card">
                <img src="https://via.placeholder.com/300x180?text=Project+1" alt="Project 1" class="project-img">
                <div class="project-content">
                    <h3>E-Commerce Platform</h3>
                    <p>A full-stack e-commerce solution with React frontend, Node.js backend, and PostgreSQL database.</p>
                    <div class="project-tech">
                        <span class="tech-tag">React</span>
                        <span class="tech-tag">Node.js</span>
                        <span class="tech-tag">PostgreSQL</span>
                    </div>
                    <a href="#" class="contact-btn">View Project</a>
                </div>
            </div>
            
            <div class="project-card">
                <img src="https://via.placeholder.com/300x180?text=Project+2" alt="Project 2" class="project-img">
                <div class="project-content">
                    <h3>Task Management App</h3>
                    <p>A collaborative task management application with real-time updates using WebSockets.</p>
                    <div class="project-tech">
                        <span class="tech-tag">Vue.js</span>
                        <span class="tech-tag">Express</span>
                        <span class="tech-tag">Socket.io</span>
                    </div>
                    <a href="#" class="contact-btn">View Project</a>
                </div>
            </div>
            
            <div class="project-card">
                <img src="https://via.placeholder.com/300x180?text=Project+3" alt="Project 3" class="project-img">
                <div class="project-content">
                    <h3>API Analytics Dashboard</h3>
                    <p>Dashboard for monitoring API performance with data visualization and custom reporting.</p>
                    <div class="project-tech">
                        <span class="tech-tag">TypeScript</span>
                        <span class="tech-tag">Python</span>
                        <span class="tech-tag">AWS</span>
                    </div>
                    <a href="#" class="contact-btn">View Project</a>
                </div>
            </div>
        </div>
    </div>
    
    <div class="container">
        <h2>GitHub Statistics</h2>
        <div class="stats">
            <div class="stat-card">
                <div class="stat-number">150+</div>
                <div class="stat-label">Contributions</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">25</div>
                <div class="stat-label">Repositories</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">15</div>
                <div class="stat-label">Stars Earned</div>
            </div>
            <div class="stat-card">
                <div class="stat-number">42</div>
                <div class="stat-label">Followers</div>
            </div>
        </div>
        
        <!-- In your actual GitHub README, you would use markdown with special tags -->
        <div style="text-align: center; margin: 30px 0;">
            <p><em>In your actual GitHub profile, you can add dynamic GitHub stats using:</em></p>
            <p>![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical)</p>
            <p>![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=yourusername&theme=radical)</p>
        </div>
    </div>
    
    <div class="container">
        <h2>Get in Touch</h2>
        <div class="contact-links">
            <a href="mailto:your.email@example.com" class="contact-btn">Email</a>
            <a href="https://linkedin.com/in/yourprofile" class="contact-btn">LinkedIn</a>
            <a href="https://twitter.com/yourusername" class="contact-btn">Twitter</a>
            <a href="https://yourportfolio.com" class="contact-btn">Portfolio</a>
        </div>
    </div>
    
    <footer>
        <p>Thanks for visiting my profile! Have a great day!</p>
        <p>⭐️ From [Niumal Silva]</p>
    </footer>
</body>
</html>
