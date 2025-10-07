# Devrex4253.github.io
Here's a small idea of what I can do!
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marno Geduld - Graphic Designer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #fafafa;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background-color: #000;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
        }
        
        nav {
            margin-top: 1rem;
        }
        
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        nav a:hover {
            color: #8fbc8f;
        }
        
        .hero {
            padding: 4rem 0;
            text-align: center;
            background-color: #fff;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
            color: #000;
            font-weight: 300;
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #666;
            margin-bottom: 2rem;
        }
        
        .about {
            padding: 3rem 0;
            background-color: #f5f5f5;
        }
        
        .about h2 {
            color: #000;
            margin-bottom: 1rem;
            font-size: 1.8rem;
            font-weight: 300;
        }
        
        .about p {
            color: #555;
            margin-bottom: 1rem;
        }
        
        .contact {
            padding: 3rem 0;
            background-color: #fff;
            text-align: center;
        }
        
        .contact h2 {
            color: #000;
            margin-bottom: 1rem;
            font-size: 1.8rem;
            font-weight: 300;
        }
        
        .contact-info {
            color: #666;
            margin-bottom: 0.5rem;
        }
        
        .btn {
            display: inline-block;
            padding: 12px 24px;
            background-color: #8fbc8f;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
            margin-top: 1rem;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #7aa87a;
        }
        
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
            font-size: 0.9rem;
        }
        
        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }
            
            nav a {
                display: block;
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Marno Geduld</h1>
            <p>Graphic Designer</p>
            <nav>
                <a href="index.html">Home</a>
                <a href="projects.html">Projects</a>
            </nav>
        </div>
    </header>

    <section class="hero">
        <div class="container">
            <h1>Creative Visual Solutions</h1>
            <p class="tagline">Minimal design with maximum impact</p>
        </div>
    </section>

    <section class="about">
        <div class="container">
            <h2>About Me</h2>
            <p>I'm a passionate graphic designer specializing in clean, minimal design that communicates effectively. With 5+ years of experience, I focus on creating visual identities that are both beautiful and functional.</p>
            <p>My approach combines strategic thinking with creative execution, ensuring every design serves its intended purpose while maintaining aesthetic excellence.</p>
            <p>Specialties: Brand Identity, Print Design, Digital Graphics, Typography</p>
        </div>
    </section>

    <section class="contact">
        <div class="container">
            <h2>Let's Work Together</h2>
            <p class="contact-info">Email: m.dev.geduld38@gmail.com</p>
            <p class="contact-info">Phone: 065 908 5378</p>
            <p class="contact-info">Location: Cape Town, South Africa</p>
            <a href="mailto:m.dev.geduld38@gmail.com" class="btn">Get In Touch</a>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Marno Geduld. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects - Marno Geduld</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #fafafa;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            background-color: #000;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
        }
        
        nav {
            margin-top: 1rem;
        }
        
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 0.9rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        nav a:hover {
            color: #8fbc8f;
        }
        
        .projects {
            padding: 4rem 0;
            background-color: #fff;
        }
        
        h1 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #000;
            font-weight: 300;
        }
        
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }
        
        .project-card {
            background-color: #f9f9f9;
            border: 1px solid #e0e0e0;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
        }
        
        .project-image {
            width: 100%;
            height: 200px;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #999;
            font-size: 0.9rem;
        }
        
        .project-info {
            padding: 1.5rem;
        }
        
        .project-title {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
            color: #000;
        }
        
        .project-description {
            color: #666;
            margin-bottom: 1rem;
        }
        
        .project-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
        }
        
        .tag {
            background-color: #8fbc8f;
            color: #fff;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 0.8rem;
        }
        
        .add-project {
            text-align: center;
            padding: 2rem;
            background-color: #f5f5f5;
            border-radius: 8px;
            margin-top: 2rem;
        }
        
        .add-project h3 {
            color: #666;
            margin-bottom: 1rem;
        }
        
        .edit-note {
            background-color: #8fbc8f;
            color: #fff;
            padding: 1rem;
            border-radius: 4px;
            margin-bottom: 2rem;
            text-align: center;
        }
        
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
            font-size: 0.9rem;
        }
        
        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }
            
            nav a {
                display: block;
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Marno Geduld</h1>
            <p>Graphic Designer</p>
            <nav>
                <a href="index.html">Home</a>
                <a href="projects.html">Projects</a>
            </nav>
        </div>
    </header>

    <section class="projects">
        <div class="container">
            <div class="edit-note">
            </div>
            
            <h1>Selected Projects</h1>
            
            <div class="project-grid">
                <!-- Project 1 -->
                <div class="project-card">
                    <div class="project-image">
                        [Project Image 1]
                    </div>
                    <div class="project-info">
                        <h3 class="project-title">Brand Identity Design</h3>
                        <p class="project-description">Complete brand identity package including logo design, color palette, and brand guidelines for a sustainable fashion startup.</p>
                        <div class="project-tags">
                            <span class="tag">Branding</span>
                            <span class="tag">Logo</span>
                            <span class="tag">Guidelines</span>
                        </div>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="project-card">
                    <div class="project-image">
                        [Project Image 2]
                    </div>
                    <div class="project-info">
                        <h3 class="project-title">Editorial Layout</h3>
                        <p class="project-description">Magazine spread design featuring clean typography and strategic use of white space for enhanced readability.</p>
                        <div class="project-tags">
                            <span class="tag">Print</span>
                            <span class="tag">Typography</span>
                            <span class="tag">Layout</span>
                        </div>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="project-card">
                    <div class="project-image">
                        [Project Image 3]
                    </div>
                    <div class="project-info">
                        <h3 class="project-title">Digital Campaign</h3>
                        <p class="project-description">Social media graphics and digital advertisements for a product launch campaign, maintaining consistent visual language.</p>
                        <div class="project-tags">
                            <span class="tag">Digital</span>
                            <span class="tag">Social Media</span>
                            <span class="tag">Campaign</span>
                        </div>
                    </div>
                </div>

                <!-- Project 4 -->
                <div class="project-card">
                    <div class="project-image">
                        [Project Image 4]
                    </div>
                    <div class="project-info">
                        <h3 class="project-title">Packaging Design</h3>
                        <p class="project-description">Minimal packaging design for organic skincare products, emphasizing sustainability and premium quality.</p>
                        <div class="project-tags">
                            <span class="tag">Packaging</span>
                            <span class="tag">Sustainable</span>
                            <span class="tag">Product</span>
                        </div>
                    </div>
                </div>
            </div>

            <div class="add-project">
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 DevrexLabs. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
