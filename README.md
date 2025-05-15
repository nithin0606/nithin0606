<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nithin M - Portfolio</title>
    <style>
        :root {
            --primary: #3498db;
            --secondary: #2c3e50;
            --accent: #e74c3c;
            --light: #ecf0f1;
            --dark: #2c3e50;
            --gray: #95a5a6;
        }    
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        } 
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }    
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
            border-radius: 10px;
            margin-top: 30px;
            margin-bottom: 30px;
        } 
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding-bottom: 20px;
            border-bottom: 2px solid var(--primary);
            margin-bottom: 30px;
        }
        .header-text h1 {
            color: var(--secondary);
            font-size: 2.5rem;
            margin-bottom: 5px;
        }
        .header-text p {
            color: var(--gray);
            font-size: 1.1rem;
        }
        .contact-info {
            text-align: right;
        }  
        .contact-info p {
            margin-bottom: 5px;
        }
        .contact-info a {
            color: var(--primary);
            text-decoration: none;
        }    
        .contact-info a:hover {
            text-decoration: underline;
        } 
        section {
            margin-bottom: 30px;
        }  
        h2 {
            color: var(--primary);
            border-bottom: 2px solid var(--light);
            padding-bottom: 5px;
            margin-bottom: 15px;
            font-size: 1.8rem;
        }
        h3 {
            color: var(--secondary);
            margin-bottom: 5px;
            font-size: 1.3rem;
        }  
        .job, .education-item, .project {
            margin-bottom: 20px;
            padding-bottom: 20px;
            border-bottom: 1px dashed var(--gray);
        }
        .job:last-child, .education-item:last-child, .project:last-child {
            border-bottom: none;
        }     
        .date {
            color: var(--gray);
            font-style: italic;
            margin-bottom: 10px;
        } 
        ul {
            padding-left: 20px;
        }  
        li {
            margin-bottom: 5px;
        }  
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
        }  
        .skill-category {
            flex: 1;
            min-width: 250px;
        }     
        .skill-category h4 {
            color: var(--accent);
            margin-bottom: 10px;
        }
        .tag {
            display: inline-block;
            background-color: var(--light);
            color: var(--dark);
            padding: 5px 10px;
            border-radius: 20px;
            margin-right: 5px;
            margin-bottom: 5px;
            font-size: 0.9rem;
        } 
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                text-align: center;
            }      
            .contact-info {
                text-align: center;
                margin-top: 15px;
            }
            .skills-container {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="header-text">
                <h1>NITHIN M</h1>
                <p>Freelance Event Manager & Aspiring Developer</p>
            </div>
            <div class="contact-info">
                <p>📧 <a href="mailto:nithinmgowda06@gmail.com">nithinmgowda06@gmail.com</a></p>
                <p>🌍 Bengaluru, India</p>
                <p>🔗 <a href="linkedin.com/in/nithinm06" target="_blank">LinkedIn</a> | 
                   <a href="https://github.com/nithin0606" target="_blank">GitHub</a></p>
            </div>
        </header>
        <section id="summary">
            <h2>Professional Summary</h2>
            <p>Dynamic and results-driven event management professional with three years of experience in corporate events, weddings, concerts, and brand promotions. Adept at orchestrating large-scale events, leading cross-functional teams, and executing seamless event operations. Passionate about technology with skills in programming and development.</p>
        </section>
        <section id="skills">
            <h2>Skills</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h4>Technical Skills</h4>
                    <div>
                        <span class="tag">Python (Intermediate)</span>
                        <span class="tag">Java (Beginner)</span>
                        <span class="tag">Data Structures & Algorithms</span>
                        <span class="tag">Machine Learning</span>
                        <span class="tag">Artificial Intelligence</span>
                        <span class="tag">SQL</span>
                        <span class="tag">MySQL</span>
                        <span class="tag">Data Analysis</span>
                        <span class="tag">Figma</span>
                        <span class="tag">Microsoft Excel</span>
                        <span class="tag">PowerPoint</span>
                    </div>
                </div>
                <div class="skill-category">
                    <h4>Event & Management Skills</h4>
                    <div>
                        <span class="tag">Strategic Event Planning</span>
                        <span class="tag">Vendor Management</span>
                        <span class="tag">Stakeholder Management</span>
                        <span class="tag">Audience Engagement</span>
                        <span class="tag">Crisis & Risk Management</span>
                        <span class="tag">Budgeting</span>
                        <span class="tag">Team Leadership</span>
                    </div>
                </div>
            </div>
        </section>        
        <section id="experience">
            <h2>Work Experience</h2>
            <div class="job">
                <h3>Freelance Event Manager</h3>
                <p class="date">2021 - Present | Bengaluru, India</p>
                <ul>
                    <li>Managed 100+ high-impact events with seamless execution and client satisfaction</li>
                    <li>Led budgeting, vendor coordination, and on-site operations for various events</li>
                    <li>Specialized in VIP and celebrity event management, enhancing experiences with strategic planning</li>
                    <li>Developed strong relationships with vendors and clients to ensure repeat business</li>
                </ul>
            </div>
        </section>        
        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Virtual Mouse</h3>
                <ul>
                    <li>Designed a hand gesture-based virtual mouse for contactless computer interaction</li>
                    <li>Technologies: Python, OpenCV, Mediapipe</li>
                </ul>
            </div>
            <div class="project">
                <h3>Food Ordering System</h3>
                <ul>
                    <li>Created a user interface for browsing menus, ordering, payments, and restaurant management</li>
                    <li>Technologies: SQL, PHP</li>
                </ul>
            </div>
            <div class="project">
                <h3>Blood Bank Management System</h3>
                <ul>
                    <li>Developed a web-based platform to manage blood donations and distribution</li>
                    <li>Technologies: SQL, PHP</li>
                </ul>
            </div>
            <div class="project">
                <h3>Multiple Disease Prediction</h3>
                <ul>
                    <li>Built an ML-based system to predict health conditions from user inputs</li>
                    <li>Technologies: Python, Streamlit</li>
                </ul>
            </div>
        </section>      
        <section id="education">
            <h2>Education</h2>
            <div class="education-item">
                <h3>Bachelor of Engineering (B.E) - Information Science</h3>
                <p class="date">2023 - Present | MVJ College of Engineering</p>
            </div>
            <div class="education-item">
                <h3>Diploma in Computer Science and Engineering</h3>
                <p class="date">2020-2023 | Sri Jayachamarajendra (Govt.) Polytechnic</p>
                <p>CGPA: 8.09/10.0</p>
            </div>
            <div class="education-item">
                <h3>SSLC (10th Std)</h3>
                <p class="date">2019-2020 | Sterling English High School</p>
                <p>Percentage: 86.4%</p>
            </div>
        </section>     
        <section id="additional">
            <h2>Additional Information</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h4>Languages</h4>
                    <div>
                        <span class="tag">English</span>
                        <span class="tag">Kannada</span>
                        <span class="tag">Hindi</span>
                        <span class="tag">Telugu</span>
                    </div>
                </div>
                <div class="skill-category">
                    <h4>Internships</h4>
                    <p>AI & ML Intern | Techlang Upskill & Earn | Mar 2023 - June 2023</p>
                </div>
                <div class="skill-category">
                    <h4>Training</h4>
                    <p>Samsung Innovation Campus | Dec 2022 - Mar 2023</p>
                </div>
                <div class="skill-category">
                    <h4>Certifications</h4>
                    <div>
                        <span class="tag">Java</span>
                        <span class="tag">SQL</span>
                        <span class="tag">Python</span>
                    </div>
                </div>
            </div>
        </section>
    </div>
</body>
</html>
