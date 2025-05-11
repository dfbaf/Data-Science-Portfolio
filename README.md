<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Data Science Portfolio</title>
    <style>
        :root {
            --primary: #0366d6; /* GitHub's blue */
            --dark: #24292e;    /* GitHub's dark */
            --light: #f6f8fa;   /* GitHub's light */
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: var(--dark);
        }
        header {
            text-align: center;
            margin-bottom: 40px;
        }
        h1 {
            color: var(--primary);
        }
        a {
            color: var(--primary);
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        .project-card {
            border: 1px solid #e1e4e8;
            border-radius: 6px;
            padding: 15px;
            transition: transform 0.2s;
        }
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            margin-top: 40px;
            color: #586069;
        }
        @media (max-width: 600px) {
            .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Data Scientist | Machine Learning Engineer</p>
        <nav>
            <a href="https://github.com/yourusername" target="_blank">GitHub</a> •
            <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a> •
            <a href="mailto:youremail@example.com">Email</a>
        </nav>
    </header>

    <section>
        <h2>About Me</h2>
        <p>Short bio highlighting your skills and what you're passionate about in data science. Keep it concise (2-3 sentences).</p>
    </section>

    <section>
        <h2>Featured Projects</h2>
        <div class="projects">
            <div class="project-card">
                <h3><a href="#">Project 1</a></h3>
                <p>Brief description (e.g., "Customer churn prediction model with 92% accuracy").</p>
                <small>Python, Scikit-learn, Pandas</small>
            </div>
            <div class="project-card">
                <h3><a href="#">Project 2</a></h3>
                <p>Brief description (e.g., "Interactive COVID-19 dashboard with Tableau").</p>
                <small>SQL, Tableau</small>
            </div>
            <!-- Add more project cards -->
        </div>
    </section>

    <footer>
        <p>© <span id="year"></span> Your Name. Hosted on GitHub Pages.</p>
    </footer>

    <script>
        // Auto-update year
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
