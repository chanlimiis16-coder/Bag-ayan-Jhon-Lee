<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

    <nav class="sidebar">
        <h2>Portfolio</h2>
        <ul>
            <li><a href="#" onclick="showSection('profile')">Profile</a></li>
            <li><a href="#" onclick="showSection('cover-letter')">Cover Letter</a></li>
            <li class="dropdown">
                <span>Table of Contents ▼</span>
                <ul class="submenu">
                    <li><a href="#" onclick="showSection('rubric')">a. Rubric</a></li>
                    <li><a href="#" onclick="showSection('grasps')">b. GRASPS Model</a></li>
                    <li><a href="#" onclick="showSection('affective')">c.1 Affective Tools</a></li>
                    <li><a href="#" onclick="showSection('interview')">c.2 Interview</a></li>
                    <li><a href="#" onclick="showSection('favorable')">d. Favorable/Not Favorable</a></li>
                    <li><a href="#" onclick="showSection('pointers')">e.1 Pointers</a></li>
                    <li><a href="#" onclick="showSection('simulation')">e.2 Simulation</a></li>
                    <li><a href="#" onclick="showSection('slide123')">f. Slide 123</a></li>
                </ul>
            </li>
            <li><a href="#" onclick="showSection('conclusion')">Conclusion</a></li>
        </ul>
    </nav>

    <main class="content">
        
        <section id="profile" class="page-section active">
            <h1>Profile</h1>
            <img src="profile-pic.jpg" alt="Profile Picture" class="profile-img">
            <p>Your personal bio goes here. Talk about your passions, goals, and skills.</p>
        </section>

        <section id="cover-letter" class="page-section">
            <h1>Cover Letter</h1>
            <div class="letter-box">
                <p>[Date]</p>
                <p>To whom it may concern...</p>
                <p>Your formal letter content goes here.</p>
            </div>
        </section>

        <section id="rubric" class="page-section">
            <h1>Rubric</h1>
            <details>
                <summary>Analytic and Holistic Rubric</summary>
                <p>Details about the rubrics used in assessment...</p>
            </details>
            <details>
                <summary>Reflection</summary>
                <p>Your thoughts on using these rubrics.</p>
            </details>
        </section>

        <section id="affective" class="page-section">
            <h1>Affective Assessment Tool</h1>
            <div class="tabs">
                <button onclick="alert('Likert Scale Details')">Likert</button>
                <button onclick="alert('Sentence Completion Details')">Sentence Completion</button>
                <button onclick="alert('Reflection content')">Written Reflection</button>
            </div>
        </section>

        <section id="simulation" class="page-section">
            <h1>Simulation</h1>
            <div class="video-container">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/your-video-id" frameborder="0" allowfullscreen></iframe>
            </div>
            <details>
                <summary>Reflection</summary>
                <p>Reflection on the simulation experience.</p>
            </details>
        </section>

        <section id="conclusion" class="page-section">
            <h1>Conclusion</h1>
            <button class="collapsible">What I have learned</button>
            <div class="collapsed-content"><p>Summary of learning...</p></div>
            
            <button class="collapsible">Letter to myself</button>
            <div class="collapsed-content"><p>Dear self...</p></div>
            
            <button class="collapsible">Letter to my parent</button>
            <div class="collapsed-content"><p>Thank you for...</p></div>
        </section>

    </main>

    <script src="script.js"></script>
</body>
</html>
