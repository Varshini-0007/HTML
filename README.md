<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Varshini Resume</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">

    <!-- LEFT SIDEBAR -->
    <div class="left">
        <h1>Varshini</h1>
        <p class="title">Software Engineer</p>

        <img src="profile.jpg" class="profile-img">

        <h3>Contact</h3>
        <ul class="info-list">
            <li>📞 9880617053</li>
            <li>📧 varshini.kushi7@gmail.com</li>
            <li>🔗 LinkedIn Profile</li>
            <li>🌍 Nationality: Indian</li>
        </ul>

        <h3>Skills</h3>
        <ul class="info-list">
            <li>C</li>
            <li>Java</li>
            <li>Python</li>
            <li>HTML, CSS, JavaScript</li>
        </ul>

        <h3>Education</h3>
        <ul class="info-list">
            <li><b>Bachelor's in Computer Science</b><br>
                Dayananda Sagar University (2016–2020)<br>
                CGPA: 9.5
            </li>
            <li><b>Master’s in Computer Science</b><br>
                MS Ramaiah University (2021–2023)
            </li>
        </ul>

        <h3>Languages</h3>
        <ul class="info-list">
            <li>Kannada</li>
            <li>English</li>
            <li>Hindi</li>
        </ul>

    </div>

    <!-- RIGHT CONTENT -->
    <div class="right">

        <section>
            <h2 class="section-title">Career Objective</h2>
            <p>
                Creative and detail-oriented software engineer with expertise in full-stack development. 
                Adept at solving problems, collaborating in teams, and building scalable software solutions.
            </p>
        </section>

        <section>
            <h2 class="section-title">Projects</h2>
            <ul>
                <li>AI-powered Resume Builder – Auto-generates resumes using templates.</li>
                <li>Smart Waste Management – IoT + AI waste tracking system.</li>
                <li>Chatbot Assistant – Python NLP chatbot for customer queries.</li>
            </ul>
        </section>

        <section>
            <h2 class="section-title">Professional Experience</h2>

            <h3>Software Engineering Intern</h3>
            <p class="company">Google India | May 2022 – Jul 2022</p>
            <ul>
                <li>Optimized search algorithms for faster performance.</li>
                <li>Implemented internal APIs with engineering teams.</li>
            </ul>

            <h3>Graduate Engineer Trainee</h3>
            <p class="company">Microsoft R&D | Aug 2023 – Present</p>
            <ul>
                <li>Developed cloud-based applications using Azure & .NET Core.</li>
                <li>Enhanced dashboards and improved UX by 20%.</li>
            </ul>
        </section>

        <section>
            <h2 class="section-title">Certifications</h2>
            <ul>
                <li>AWS Certified Solutions Architect</li>
                <li>Oracle Certified Java Programmer</li>
                <li>Python for Data Science – Coursera</li>
            </ul>
        </section>

    </div>

</div>

</body>
</html>
# HTML




body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f2f2f2;
}

.container {
    display: flex;
    width: 100%;
}

/* LEFT PANEL */
.left {
    width: 30%;
    background: #ffffff;
    padding: 30px;
    box-sizing: border-box;
    border-right: 2px solid #ddd;
}

.left h1 {
    margin: 0;
    font-size: 32px;
}

.title {
    font-size: 18px;
    color: #888;
    margin-bottom: 20px;
}

.profile-img {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    margin-bottom: 20px;
}

h3 {
    background: #5cb3bd;
    color: white;
    padding: 6px 10px;
    border-radius: 6px;
    margin-top: 20px;
}

.info-list {
    list-style: none;
    padding-left: 10px;
}

.info-list li {
    margin: 8px 0;
    font-size: 15px;
}

/* RIGHT CONTENT */
.right {
    width: 70%;
    background: #5c3e1d;
    color: white;
    padding: 40px;
    box-sizing: border-box;
}

.section-title {
    background: #88b04b;
    display: inline-block;
    padding: 6px 14px;
    border-radius: 10px;
}

section {
    margin-bottom: 30px;
}

.company {
    font-style: italic;
    margin-top: -8px;
    color: #e4e4e4;
}

.right ul {
    margin-left: 20px;
}
