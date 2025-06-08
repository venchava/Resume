<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Senior .NET Developer Resume</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #2c3e50, #3498db);
            color: white;
            padding: 40px;
            text-align: center;
            position: relative;
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="50" cy="50" r="1" fill="white" opacity="0.1"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>');
            opacity: 0.1;
        }
        
        .name {
            font-size: 2.5em;
            font-weight: 300;
            margin-bottom: 10px;
            position: relative;
            z-index: 1;
        }
        
        .title {
            font-size: 1.3em;
            opacity: 0.9;
            position: relative;
            z-index: 1;
        }
        
        .contact-info {
            margin-top: 20px;
            position: relative;
            z-index: 1;
        }
        
        .contact-info span {
            margin: 0 15px;
            font-size: 0.95em;
        }
        
        .content {
            padding: 40px;
        }
        
        .section {
            margin-bottom: 40px;
        }
        
        .section-title {
            font-size: 1.4em;
            color: #2c3e50;
            border-bottom: 3px solid #3498db;
            padding-bottom: 8px;
            margin-bottom: 25px;
            position: relative;
        }
        
        .section-title::after {
            content: '';
            position: absolute;
            bottom: -3px;
            left: 0;
            width: 50px;
            height: 3px;
            background: #e74c3c;
        }
        
        .experience-item {
            margin-bottom: 30px;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 10px;
            border-left: 4px solid #3498db;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .experience-item:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .job-title {
            font-size: 1.2em;
            font-weight: 600;
            color: #2c3e50;
            margin-bottom: 5px;
        }
        
        .company {
            color: #3498db;
            font-weight: 500;
            margin-bottom: 5px;
        }
        
        .duration {
            color: #666;
            font-size: 0.9em;
            margin-bottom: 15px;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        
        .skill-category {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            border-top: 4px solid #3498db;
        }
        
        .skill-category h4 {
            color: #2c3e50;
            margin-bottom: 15px;
            font-size: 1.1em;
        }
        
        .skill-tag {
            display: inline-block;
            background: linear-gradient(135deg, #3498db, #2980b9);
            color: white;
            padding: 5px 12px;
            margin: 3px;
            border-radius: 20px;
            font-size: 0.85em;
            font-weight: 500;
        }
        
        .certification {
            background: #e8f5e8;
            border: 1px solid #27ae60;
            border-radius: 8px;
            padding: 15px;
            margin-bottom: 15px;
        }
        
        .cert-title {
            font-weight: 600;
            color: #27ae60;
            margin-bottom: 5px;
        }
        
        .responsibilities {
            list-style: none;
            padding-left: 0;
        }
        
        .responsibilities li {
            margin-bottom: 8px;
            padding-left: 20px;
            position: relative;
        }
        
        .responsibilities li::before {
            content: "▶";
            color: #3498db;
            position: absolute;
            left: 0;
            top: 0;
        }
        
        @media (max-width: 768px) {
            .container {
                margin: 10px;
                border-radius: 10px;
            }
            
            .header {
                padding: 30px 20px;
            }
            
            .name {
                font-size: 2em;
            }
            
            .content {
                padding: 30px 20px;
            }
            
            .contact-info span {
                display: block;
                margin: 5px 0;
            }
        }
        
        .print-button {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: #3498db;
            color: white;
            border: none;
            border-radius: 50px;
            padding: 15px 20px;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(52, 152, 219, 0.3);
            transition: all 0.3s ease;
        }
        
        .print-button:hover {
            background: #2980b9;
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(52, 152, 219, 0.4);
        }
        
        @media print {
            body {
                background: white;
                padding: 0;
            }
            
            .container {
                box-shadow: none;
                border-radius: 0;
            }
            
            .print-button {
                display: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1 class="name">Senior .NET Developer</h1>
            <p class="title">Full-Stack Developer | Cloud Solutions Architect</p>
            <div class="contact-info">
                <span>📧 your.email@example.com</span>
                <span>📱 +1 (555) 123-4567</span>
                <span>🔗 linkedin.com/in/yourprofile</span>
                <span>💻 github.com/yourusername</span>
            </div>
        </div>
        
        <div class="content">
            <div class="section">
                <h2 class="section-title">Professional Summary</h2>
                <p>Highly skilled Senior .NET Developer with 8+ years of experience in designing and implementing scalable enterprise solutions. AWS Certified Solutions Architect with expertise in cloud-native architectures, microservices, and modern web technologies. Proven track record of delivering robust applications for financial services and industrial automation sectors.</p>
            </div>
            
            <div class="section">
                <h2 class="section-title">Professional Experience</h2>
                
                <div class="experience-item">
                    <div class="job-title">Senior .NET Developer</div>
                    <div class="company">LPL Financial</div>
                    <div class="duration">2023 - Present</div>
                    <ul class="responsibilities">
                        <li>Architect and develop high-performance financial applications using .NET Core and Angular</li>
                        <li>Implement microservices architecture with Docker and Kubernetes on AWS</li>
                        <li>Design real-time data processing solutions using Confluent Kafka and MongoDB</li>
                        <li>Manage CI/CD pipelines with GitHub Actions and Terraform for infrastructure as code</li>
                        <li>Optimize database performance and implement caching strategies with Redis</li>
                        <li>Collaborate with cross-functional teams to deliver scalable financial solutions</li>
                    </ul>
                </div>
                
                <div class="experience-item">
                    <div class="job-title">Full-Stack .NET Developer</div>
                    <div class="company">Siemens</div>
                    <div class="duration">2021 - 2023</div>
                    <ul class="responsibilities">
                        <li>Developed industrial automation solutions using .NET Core and Angular</li>
                        <li>Implemented IoT data collection and processing systems with Azure services</li>
                        <li>Built responsive web applications with TypeScript and modern frontend frameworks</li>
                        <li>Designed RESTful APIs and integrated with third-party manufacturing systems</li>
                        <li>Maintained and optimized SQL Server databases for high-volume industrial data</li>
                        <li>Implemented automated testing strategies and improved code quality metrics</li>
                    </ul>
                </div>
                
                <div class="experience-item">
                    <div class="job-title">.NET Developer</div>
                    <div class="company">IDS Next Business Solutions</div>
                    <div class="duration">2017 - 2021</div>
                    <ul class="responsibilities">
                        <li>Developed enterprise web applications using ASP.NET MVC and Web API</li>
                        <li>Created dynamic user interfaces with JavaScript, jQuery, and early Angular versions</li>
                        <li>Designed and optimized relational database schemas in SQL Server</li>
                        <li>Implemented authentication and authorization mechanisms for business applications</li>
                        <li>Participated in agile development processes and code review practices</li>
                        <li>Provided technical support and mentored junior developers</li>
                    </ul>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">Technical Skills</h2>
                <div class="skills-grid">
                    <div class="skill-category">
                        <h4>Backend Technologies</h4>
                        <span class="skill-tag">.NET Core</span>
                        <span class="skill-tag">ASP.NET MVC</span>
                        <span class="skill-tag">Web API</span>
                        <span class="skill-tag">Entity Framework</span>
                        <span class="skill-tag">C#</span>
                    </div>
                    
                    <div class="skill-category">
                        <h4>Frontend Technologies</h4>
                        <span class="skill-tag">Angular</span>
                        <span class="skill-tag">TypeScript</span>
                        <span class="skill-tag">JavaScript</span>
                        <span class="skill-tag">HTML5</span>
                        <span class="skill-tag">CSS3</span>
                    </div>
                    
                    <div class="skill-category">
                        <h4>Cloud & DevOps</h4>
                        <span class="skill-tag">AWS</span>
                        <span class="skill-tag">Terraform</span>
                        <span class="skill-tag">GitHub Actions</span>
                        <span class="skill-tag">Docker</span>
                        <span class="skill-tag">Kubernetes</span>
                    </div>
                    
                    <div class="skill-category">
                        <h4>Databases & Messaging</h4>
                        <span class="skill-tag">SQL Server</span>
                        <span class="skill-tag">MongoDB</span>
                        <span class="skill-tag">Confluent Kafka</span>
                        <span class="skill-tag">Redis</span>
                        <span class="skill-tag">PostgreSQL</span>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">Certifications</h2>
                <div class="certification">
                    <div class="cert-title">AWS Certified Solutions Architect</div>
                    <div>Amazon Web Services - Cloud architecture design and implementation</div>
                </div>
            </div>
            
            <div class="section">
                <h2 class="section-title">Key Achievements</h2>
                <ul class="responsibilities">
                    <li>Successfully migrated legacy monolithic applications to microservices architecture, improving scalability by 300%</li>
                    <li>Implemented automated CI/CD pipelines reducing deployment time from hours to minutes</li>
                    <li>Designed high-availability systems processing millions of financial transactions daily</li>
                    <li>Led performance optimization initiatives resulting in 40% improvement in application response times</li>
                    <li>Mentored 5+ junior developers and contributed to technical decision-making processes</li>
                </ul>
            </div>
        </div>
    </div>
    
    <button class="print-button" onclick="window.print()">🖨️ Print Resume</button>
    
    <script>
        // Add smooth scrolling for better UX
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Add intersection observer for animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };
        
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);
        
        // Observe all sections for scroll animations
        document.querySelectorAll('.section').forEach(section => {
            section.style.opacity = '0';
            section.style.transform = 'translateY(20px)';
            section.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
            observer.observe(section);
        });
    </script>
</body>
</html>
