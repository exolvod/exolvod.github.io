<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Exolvo</title>
    <style>
    body {
        font-family: 'Segoe UI', Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f9ff; /* Light blue background */
        color: #333;
    }
    .container {
        max-width: 960px;
        margin: 40px auto;
        padding: 20px;
        background: #ffffff;
        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        border-radius: 8px;
    }
    header {
        color: #fff;
        background: linear-gradient(135deg, #5d8aa8 0%, #89bceb 100%);
        padding: 50px 20px;
        border-radius: 8px 8px 0 0;
        background-size: cover;
        text-align: center;
    }
    section {
        margin: 30px 0;
        padding: 30px;
        background: #fff;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        position: relative;
        overflow: hidden; /* Ensures no overlap of content and borders */
    }
    h2 {
        font-size: 24px;
        color: #5d8aa8;
        background: #ffffff;
        padding: 15px 30px;
        border-radius: 50px;
        box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        display: block; /* Changed from inline-block to block */
        width: fit-content;
        margin: -20px auto 10px; /* Adjust positioning */
        position: relative;
        z-index: 2; /* Ensures text is above any other content */
    }
    img.icon {
        height: 40px; /* Smaller icons for subtlety */
        position: absolute;
        top: 20px; /* Adjust based on your layout needs */
        right: 20px;
        z-index: 1; /* Icons below text for better readability */
    }
    ul, p {
        line-height: 1.8;
    }
    ul {
        padding-left: 40px; /* Enhanced list indentation for clarity */
    }
    footer {
        background-color: #5d8aa8;
        color: white;
        text-align: center;
        padding: 20px;
        margin-top: 40px;
        border-radius: 0 0 8px 8px;
    }
</style>
</head>
<body>

<header>
    <h1>About Exolvo</h1>
    <p>Bringing Software Engineering to Machine Learning Deployments</p>
</header>

<div class="container">
    <section>
        <h2>Goals</h2>
        <img src="/images/goals-icon.png" class="icon" alt="Goals Icon">
        <p>We aim to push the boundaries of technology to deliver solutions that enhance efficiency and reliability. Our goal is to support our clients in achieving their objectives by providing top-notch engineering solutions with unparalleled technical support.</p>
    </section>
    <section>
        <h2>What We Offer</h2>
        <img src="/images/offer-icon.png" class="icon" alt="Offer Icon">
        <ul>
            <li><strong>Custom AI Solutions</strong>: Tailored AI solutions to meet your unique business needs, including capabilities such as Agent Orchestration, Visual Processing, Knowledge Base Development, and Fine-Tuning Models.</li>
            <li><strong>Engineering Services</strong>: Advanced engineering solutions to ensure robust project execution and system integration.</li>
            <li><strong>Consulting Services</strong>: Expert advice and strategies to optimize your IT infrastructure and operations.</li>
        </ul>
    </section>
    <section>
        <h2>Our Expertise</h2>
        <img src="/images/procket.png" class="icon" alt="Expertise Icon">
        <p>Our technical expertise spans across various fields including:</p>
        <ul>
            <li>Server Side Development: Microservices, containerization, database design, SQL/NoSQL, observability and monitoring</li>
            <li>Programming Languages: Go, Python, TypeScript</li>
            <li>Data Management: Data backup, ETL, REST APIs, and backend development</li>
            <li>Databases: PostgreSQL, MongoDB, SQL Server, Redis</li>
            <li>DevOps: Infrastructure as code, CI/CD integration, high availability, cloud solutions (AWS/GCP)</li>
            <li>InfoSec: Application hardening, pen testing, security scans, and remediations</li>
            <li>MLOps: Deploy your machine learning models in production securely on-premise or in the cloud</li>
            <li>Front End Development: Single-page applications, UI frameworks, React, Next.js</li>
        </ul>
    </section>
    <section>
        <h2>Experience</h2>
        <p>Our team has extensive experience working on diverse projects, such as:</p>
        <ul>
            <li>Developing a Go data backup application</li>
            <li>Enhancing search-and-rescue antenna configurations</li>
            <li>Implementing robust data processing systems</li>
            <li>Cloud-based project database at petabyte scale</li>
            <li>Multisite command and control software with hardware sensor integration</li>
            <li>On-demand cloud resourcing deployment</li>
        </ul>
    </section>
</div>

<footer>
    At Exolvo, we are committed to excellence and innovation. Contact us today to learn how we can help you achieve your goals.
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Exolvo</title>
    <style>
    body {
        font-family: 'Open Sans', Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f9f9f9;
        color: #333;
        background: linear-gradient(to bottom right, #BDD4E7 0%, #E6E9F0 100%);
    }
    .container {
        max-width: 1000px;
        margin: auto;
        padding: 30px;
        background: #fff;
        box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        border-radius: 8px;
    }
    header, h1, h2 {
        text-align: center;
    }
    header {
        padding: 50px 20px;
    }
    section {
        background: #ffffff;
        margin: 20px 0;
        padding: 20px;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    h1 {
        font-size: 28px;
        color: #0056b3;
    }
    h2 {
        font-size: 24px;
        background-color: #5D8AA8;
        color: #ffffff;
        padding: 15px 25px;
        border-radius: 30px;
        box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        display: inline-block;
        margin: 10px auto;
        width: fit-content;
    }
    ul, p {
        line-height: 1.8;
        font-size: 16px;
    }
    ul {
        padding-left: 40px;
    }
    footer {
        background-color: #2c3e50;
        color: white;
        text-align: center;
        padding: 20px;
        margin-top: 40px;
    }
    .button {
        background: linear-gradient(to right, #5D8AA8, #89BCEB);
        color: #fff;
        padding: 10px 20px;
        text-decoration: none;
        border-radius: 5px;
        transition: background 0.3s ease;
    }
    .button:hover {
        background: linear-gradient(to right, #89BCEB, #5D8AA8);
    }
</style>

</head>
<body>

<header>
    <h1>About Exolvo</h1>
    <p>Bringing Software Engineering to Machine Learning Deployments</p>
</header>

<div class="container">
    <section>
        <h2>Goals</h2>
        <p>We aim to push the boundaries of technology to deliver solutions that enhance efficiency and reliability. Our goal is to support our clients in achieving their objectives by providing top-notch engineering solutions with unparalleled technical support.</p>
    </section>
    <section>
        <h2>What We Offer</h2>
        <ul>
            <li><strong>Custom AI Solutions</strong>: Tailored AI solutions to meet your unique business needs, including capabilities such as Agent Orchestration, Visual Processing, Knowledge Base Development, and Fine-Tuning Models.</li>
            <li><strong>Engineering Services</strong>: Advanced engineering solutions to ensure robust project execution and system integration.</li>
            <li><strong>Consulting Services</strong>: Expert advice and strategies to optimize your IT infrastructure and operations.</li>
        </ul>
    </section>
    <section>
        <h2>Our Expertise</h2>
        <p>Our technical expertise spans across various fields including:</p>
        <ul>
            <li>Server Side Development: Microservices, containerization, database design, SQL/NoSQL, observability and monitoring</li>
            <li>Programming Languages: Go, Python, TypeScript</li>
            <li>Data Management: Data backup, ETL, REST APIs, and backend development</li>
            <li>Databases: PostgreSQL, MongoDB, SQL Server, Redis</li>
            <li>DevOps: Infrastructure as code, CI/CD integration, high availability, cloud solutions (AWS/GCP)</li>
            <li>InfoSec: Application hardening, pen testing, security scans, and remediations</li>
            <li>MLOps: Deploy your machine learning models in production securely on-premise or in the cloud</li>
            <li>Front End Development: Single-page applications, UI frameworks, React, Next.js</li>
        </ul>
    </section>
    <section>
        <h2>Experience</h2>
        <p>Our team has extensive experience working on diverse projects, such as:</p>
        <ul>
            <li>Developing a Go data backup application</li>
            <li>Enhancing search-and-rescue antenna configurations</li>
            <li>Implementing robust data processing systems</li>
            <li>Cloud-based project database at petabyte scale</li>
            <li>Multisite command and control software with hardware sensor integration</li>
            <li>On-demand cloud resourcing deployment</li>
        </ul>
    </section>
</div>

<footer>
    At Exolvo, we are committed to excellence and innovation. Contact us today to learn how we can help you achieve your goals.
</footer>

</body>
</html>

---
title: "About Us"
---

# Exolvo: Bringing Software Engineering to Machine Learning Deployments

At Exolvo, we specialize in providing cutting-edge solutions in Artificial Intelligence, Engineering, and Consulting services geared toward tactical coordination. Our team of experts is dedicated to creating resilient and innovative products that meet the dynamic needs of our clients.

## Goals

We aim to push the boundaries of technology to deliver solutions that enhance efficiency and reliability. Our goal is to support our clients in achieving their objectives by providing top-notch engineering solutions with unparalleled technical support.

## What We Offer

- **Custom AI Solutions**: Tailored AI solutions to meet your unique business needs, including capabilities such as:
  - Agent Orchestration
  - Visual Processing
  - Knowledge Base Development
  - Fine-Tuning Models
- **Engineering Services**: Advanced engineering solutions to ensure robust project execution and system integration
- **Consulting Services**: Expert advice and strategies to optimize your IT infrastructure and operations

## Our Expertise

Our technical expertise spans across various fields including:

- **Server Side Development**: Microservices, containerization, database design, SQL/NoSQL, observability and monitoring
- **Programming Languages**: Go, Python, TypeScript
- **Data Management**: Data backup, ETL, REST APIs, and backend development
- **Databases**: PostgreSQL, MongoDB, SQL Server, Redis
- **DevOps**: Infrastructure as code, CI/CD integration, high availability, cloud solutions (AWS/GCP)
- **InfoSec**: Application hardening, pen testing, security scans, and remediations
- **MLOps**: Deploy your machine learning models in production securely on-premise or in the cloud
- **Front End Development**: Single-page applications, UI frameworks, React, Next.js

## Experience

Our team has extensive experience working on diverse projects, such as:

- Developing a Go data backup application
- Enhancing search-and-rescue antenna configurations
- Implementing robust data processing systems
- Cloud-based project database at petabyte scale
- Multisite command and control software with hardware sensor integration
- On-demand cloud resourcing deployment


---

At Exolvo, we are committed to excellence and innovation. Contact us today to learn how we can help you achieve your goals.



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Exolvo</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        .header {
            padding: 40px 20px;
            background: #0056b3;
            color: white;
            text-align: center;
        }
        .container {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            max-width: 1200px;
            margin: 40px auto;
        }
        .card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            padding: 20px;
            width: 30%;
            text-align: center;
            position: relative;
        }
        .card h2 {
            color: #0056b3;
        }
        .icon {
            height: 50px;
            margin-bottom: 20px;
        }
        .content {
            display: none;
            padding: 10px;
            text-align: left;
            font-size: 14px;
            border-top: 1px solid #ccc;
            margin-top: 10px;
        }
        button {
            background: #0077cc;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            margin-top: 10px;
        }
        button:hover {
            background: #005fa3;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #2c3e50;
            color: white;
        }
    </style>
    <script>
        function toggleContent(id) {
            var content = document.getElementById(id);
            content.style.display = content.style.display === 'block' ? 'none' : 'block';
        }
    </script>
</head>
<body>

<div class="header">
    <h1>About Exolvo</h1>
    <p>Bringing Software Engineering to Machine Learning Deployments</p>
</div>

At Exolvo, we specialize in providing cutting-edge solutions in Artificial Intelligence, Engineering, and Consulting services geared toward tactical coordination. Our team of experts is dedicated to creating resilient and innovative products that meet the dynamic needs of our clients.

<div class="container">
    <div class="card">
        <img src="/images/goalicon2.png" class="icon" alt="Goals Icon">
        <h2>Goals</h2>
        <p>We aim to push the boundaries of technology to deliver solutions that enhance efficiency and reliability.</p>
        <button onclick="toggleContent('goals-content')">Learn More</button>
        <div class="content" id="goals-content">
            <p>We aim to push the boundaries of technology to deliver solutions that enhance efficiency and reliability. Our goal is to support our clients in achieving their objectives by providing top-notch engineering solutions with unparalleled technical support.</p>
        </div>
    </div>
    <div class="card">
        <img src="/images/offericon.png" class="icon" alt="Offer Icon">
        <h2>What We Offer</h2>
        <p>Custom AI, Engineering Services, and Consulting.</p>
        <button onclick="toggleContent('offer-content')">Learn More</button>
        <div class="content" id="offer-content">
            <p><strong>Custom AI Solutions:</strong> Tailored AI solutions to meet your unique business needs, including capabilities such as:</p>
            <ul>
                <li>Agent Orchestration</li>
                <li>Visual Processing</li>
                <li>Knowledge Base Development</li>
                <li>Fine-Tuning Models</li>
            </ul>
            <p><strong>Engineering Services:</strong> Advanced engineering solutions to ensure robust project execution and system integration.</p>
            <p><strong>Consulting Services:</strong> Expert advice and strategies to optimize your IT infrastructure and operations.</p>
        </div>
    </div>
    <div class="card">
        <img src="/images/expertiseicon.png" class="icon" alt="Expertise Icon">
        <h2>Our Expertise</h2>
        <p>Our technical expertise spans across various fields.</p>
        <button onclick="toggleContent('expertise-content')">Learn More</button>
        <div class="content" id="expertise-content">
            <ul>
                <li>Server Side Development: Microservices, containerization, database design, SQL/NoSQL, observability and monitoring</li>
                <li>Programming Languages: Go, Python, TypeScript</li>
                <li>Data Management: Data backup, ETL, REST APIs, and backend development</li>
                <li>Databases: PostgreSQL, MongoDB, SQL Server, Redis</li>
                <li>DevOps: Infrastructure as code, CI/CD integration, high availability, cloud solutions (AWS/GCP)</li>
                <li>InfoSec: Application hardening, pen testing, security scans, and remediations</li>
                <li>MLOps: Deploy your machine learning models in production securely on-premise or in the cloud</li>
                <li>Front End Development: Single-page applications, UI frameworks, React, Next.js</li>
            </ul>
        </div>
    </div>
    <!-- Card for Experience -->
    <div class="card">
        <img src="/images/experienceicon.png" class="icon" alt="Experience Icon">
        <h2>Experience</h2>
        <p>Our team has extensive experience working on diverse projects.</p>
        <button onclick="toggleContent('experience-content')">Learn More</button>
        <div class="content" id="experience-content">
            <ul>
                <li>Developing a Go data backup application</li>
                <li>Enhancing search-and-rescue antenna configurations</li>
                <li>Implementing robust data processing systems</li>
                <li>Cloud-based project database at petabyte scale</li>
                <li>Multisite command and control software with hardware sensor integration</li>
                <li>On-demand cloud resourcing deployment</li>
            </ul>
        </div>
    </div>
</div>

<footer>
    At Exolvo, we are committed to excellence and innovation. Contact us today to learn how our solutions can help you achieve your goals.
</footer>

</body>
</html>