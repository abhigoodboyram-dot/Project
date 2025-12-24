<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Engineering Notes Hub</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(120deg, #3b82f6, #9333ea);
            color: white;
        }

        header {
            text-align: center;
            padding: 40px 20px;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        header p {
            margin-top: 10px;
            font-size: 16px;
            opacity: 0.9;
        }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 25px;
            padding: 40px;
            max-width: 1000px;
            margin: auto;
        }

        .card {
            background: #e6f7f7;
            color: #111;
            padding: 25px;
            border-radius: 15px;
            text-decoration: none;
            transition: 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
        }

        .card h2 {
            margin: 0;
            color: #2563eb;
        }

        .card p {
            margin-top: 10px;
            font-size: 14px;
        }

        footer {
            text-align: center;
            padding: 20px;
            opacity: 0.8;
            font-size: 14px;
        }
    </style>
</head>

<body>

<header>
    <h1>📘 Engineering Notes Hub</h1>
    <p>All your semester notes in one place</p>
</header>

<div class="container">

    <a class="card" href="https://www.scribd.com/document/786701384/Basic-Electrical-Engineering-BEE-1st-Year-B-Tech-Class-Notes" target="_blank">
        <h2>BEEE</h2>
        <p>Basic Electrical & Electronics Engineering</p>
    </a>

    <a class="card" href="https://aitskadapa.ac.in/img/pdf/LAC-min.pdf" target="_blank">
        <h2>LA & C</h2>
        <p>Linear Algebra & Calculus</p>
    </a>

    <a class="card" href="https://www.scribd.com/document/514329584/Engineering-Physics-I-Notes-All-Modules" target="_blank">
        <h2>EP</h2>
        <p>Engineering Physics</p>
    </a>

    <a class="card" href="https://www.scribd.com/document/139395917/Unit-1-Introduction-to-Programming" target="_blank">
        <h2>IP</h2>
        <p>Introduction to Programming</p>
    </a>

</div>

<footer>
    © 2025 Engineering Notes Hub
</footer>

</body>
</html>
