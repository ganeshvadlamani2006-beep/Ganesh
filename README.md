# Ganesh
Cancer awareness 
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Cancer Awareness</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f6f9;
        }

        header {
            background-color: #b30000;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #800000;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 30px;
        }

        h2 {
            color: #b30000;
        }

        .card {
            background: white;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        footer {
            background-color: #800000;
            color: white;
            text-align: center;
            padding: 15px;
        }

        .btn {
            background-color: #b30000;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
        }

        .btn:hover {
            background-color: #800000;
        }
    </style>
</head>
<body>

<header>
    <h1>Cancer Awareness Website</h1>
    <p>Spreading Knowledge | Saving Lives</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#types">Types</a>
    <a href="#symptoms">Symptoms</a>
    <a href="#prevention">Prevention</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Cancer</h2>
    <div class="card">
        <p>
            Cancer is a disease in which some of the body's cells grow uncontrollably 
            and spread to other parts of the body. Early detection and treatment can 
            improve survival rates.
        </p>
    </div>
</section>

<section id="types">
    <h2>Common Types of Cancer</h2>
    <div class="card">
        <ul>
            <li>Breast Cancer</li>
            <li>Lung Cancer</li>
            <li>Prostate Cancer</li>
            <li>Skin Cancer</li>
            <li>Blood Cancer (Leukemia)</li>
        </ul>
    </div>
</section>

<section id="symptoms">
    <h2>Common Symptoms</h2>
    <div class="card">
        <ul>
            <li>Unexplained weight loss</li>
            <li>Persistent fatigue</li>
            <li>Unusual bleeding</li>
            <li>Persistent cough</li>
            <li>Lumps or swelling</li>
        </ul>
    </div>
</section>

<section id="prevention">
    <h2>Prevention & Awareness</h2>
    <div class="card">
        <ul>
            <li>Avoid tobacco</li>
            <li>Healthy diet & exercise</li>
            <li>Regular medical checkups</li>
            <li>Vaccinations (HPV, Hepatitis B)</li>
        </ul>
        <br>
        <a href="#" class="btn">Learn More</a>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <div class="card">
        <p>Email: support@cancerawareness.org</p>
        <p>Phone: +91 98765 43210</p>
    </div>
</section>

<footer>
    <p>© 2026 Cancer Awareness | All Rights Reserved</p>
</footer>

</body>
</html>
