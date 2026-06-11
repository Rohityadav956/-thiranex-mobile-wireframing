<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile App Wireframing | Thiranex Project</title>
    <style>
        :root {
            --primary-color: #1e40af;
            --text-color: #334155;
            --bg-color: #f8fafc;
            --card-bg: #ffffff;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 40px auto;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 40px;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 20px;
        }
        h1 { color: var(--primary-color); margin-bottom: 10px; }
        .tag {
            background-color: #dbeafe;
            color: var(--primary-color);
            padding: 4px 12px;
            border-radius: 9999px;
            font-size: 0.85rem;
            font-weight: 600;
        }
        .card {
            background: var(--card-bg);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1);
            margin-bottom: 25px;
        }
        h2 { color: #0f172a; border-left: 4px solid var(--primary-color); padding-left: 10px; }
        ul { padding-left: 20px; }
        li { margin-bottom: 8px; }
        .btn {
            display: inline-block;
            background-color: var(--primary-color);
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 6px;
            font-weight: bold;
            margin-top: 15px;
            transition: background 0.2s;
        }
        .btn:hover { background-color: #1d4ed8; }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Mobile App Wireframing</h1>
            <span class="tag">Thiranex Assignment 1</span>
        </header>

        <div class="card">
            <h2>Project Overview</h2>
            <p>This project focuses on early-stage design planning, mapping user flows, and creating low-fidelity wireframes to solve complex mobile application navigational challenges.</p>
            <!-- REPLACE THE LINK BELOW WITH YOUR ACTUAL FIGMA/ADOBE XD LINK -->
            <a href="https://www.figma.com" target="_blank" class="btn">View Interactive Prototype</a>
        </div>

        <div class="card">
            <h2>Key Features Implemented</h2>
            <ul>
                <li><strong>User Research:</strong> Conducted basic competitive analysis to define user goals and paint points.</li>
                <li><strong>User Personas & Flows:</strong> Outlined logical step-by-step pathways for standard tasks.</li>
                <li><strong>Low-Fidelity Wireframes:</strong> Constructed 3 core screens focusing strictly on data architecture, layouts, and interactive elements.</li>
            </ul>
        </div>

        <div class="card">
            <h2>Expected Outcome</h2>
            <p>Developing a strict grasp on spatial distribution, reducing cognitive friction for the user, and establishing a consistent wireframing UI kit before high-fidelity visual design iterations take place.</p>
        </div>
    </div>

</body>
</html>
