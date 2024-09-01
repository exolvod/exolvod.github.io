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
        background-color: #F8F9FF; /* Light background color */
        color: #4C4F65; /* Darker grayish-purple text color */
    }
    .header-container {
    background-color: #000000; /* Dark black background */
    border-radius: 15px; /* Curved corners */
    padding: 22px 22px; /* Increase padding for a larger box */
    text-align: center;
    margin-top: 1px;
    margin-bottom: 50px;
    max-width: 1000px; /* Increase the max-width to make the box wider */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Optional shadow effect */
    }
    .header-title {
        font-size: 40px; /* Increase font size */
        font-weight: bold;
        color: #FFFFFF; /* White text color */
    }
    .header-subtitle {
        font-size: 24px; /* Increase font size */
        color: #FFFFFF; /* White text color */
    }
    .circle-image-container {
        text-align: center;
        margin-bottom: 30px;
    }
    .circle-image {
        width: 300px; /* Adjust the size as needed */
        height: 300px; /* Ensure the height matches the width for a perfect circle */
        border-radius: 50%; /* Make the image circular */
        object-fit: cover; /* Ensures the image covers the entire circle */
        display: block;
        margin: 0 auto;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Optional shadow effect */
    }
    .main-paragraph {
        max-width: 800px;
        margin: 0 auto;
        text-align: center;
        padding: 35px;
        font-size: 50px; /* Adjust font size */
        line-height: 1.6; /* Adjust line spacing */
        color: #000000; /* Darker grayish-purple text color */
    }
    .header::before {
        content: "";
        background-image: url('/images/logop1.png'); 
        background-size: cover; /* Ensures the image covers the entire section */
        background-position: center; /* Centers the image */
        background-repeat: no-repeat; /* Prevents the image from repeating */
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        z-index: -1; /* Place the image behind the content */
    }
    .header h1 {
        font-size: 40px; /* Adjust font size for larger circle */
        margin-bottom: 15px;
        color: #6A5ACD;  /*White text color for contrast */
    }
    .header p {
        font-size: 16px; /* Adjust font size for larger circle */
        margin-bottom: 10px;
        color: #FFFFFF; /* White text color for contrast */
        text-align: center; /* Center the text */
        padding: 0 20px; /* Add some padding to ensure text doesn't touch edges */
    }
    .container {
        max-width: 1100px;
        margin: 0 auto;
        padding: 20px;
    }
    .section {
    background-color: #E9F0FF; /* Light blue background color */
    border-radius: 25px; /* Rounded corners */
    padding: 40px;
    margin-bottom: 30px;
    box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1); /* Softer, larger shadow for bubble effect */
    display: flex;
    align-items: center; /* Align items to the center */
    justify-content: flex-start; /* Align items to the start (left) */
    }
    .section:nth-child(even) {
        background-color: #DCEBFE; /* Slightly darker blue for alternating sections */
    }
    .section h2 {
        font-size: 28px;
        margin-bottom: 20px;
        color: #6A5ACD; /* Purple color for section titles */
        width: 100%;
        text-align: left; /* Align title to the top left */
    }
    .section p, .section ul {
        font-size: 16px;
        line-height: 1.6;
        color: #4C4F65; /* Darker grayish-purple text color */
        margin-top: 0; /* Ensure paragraphs start immediately under headings */
    }
    .section ul {
        list-style-type: disc;
        padding-left: 20px;
    }
    .section-image {
        flex-shrink: 0;
        width: 80px; /* Reduced width for the image */
        height: 80px; /* Reduced height for the image */
        margin-right: 20px;
        border-radius: 50%; /* Make image round */
        overflow: hidden;
        background-color: #fff; /* White background to create the bubble effect */
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .section-image img {
        width: 70%; /* Slightly increased size of image within the circle */
        height: 70%;
        object-fit: contain;
    }
    .section-content {
        flex-grow: 1; /* Make sure the content takes up the remaining space */
        padding-left: 20px; /* Add padding for better separation between image and content */
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
    footer {
        background-color: #DCEBFE;
        color: white;
        text-align: center;
        padding: 20px;
        margin-top: 40px;
        border-radius: 0 0 8px 8px;
    }
</style>

</head>
<body>

<div class="header-container">
    <div class="header-title">
        About Exolvo
    </div>
    <div class="header-subtitle">
        Bringing Software Engineering to Machine Learning Deployments
    </div>
</div>

<div class="circle-image-container">
    <img src="/images/logop1.png" alt="Exolvo Image" class="circle-image">
</div>

<div class="main-paragraph">
    <p>At Exolvo, we specialize in providing cutting-edge solutions in Artificial Intelligence, Engineering, and Consulting services geared toward tactical coordination. Our team of experts is dedicated to creating resilient and innovative products that meet the dynamic needs of our clients.</p>
</div>

<div class="container">
    <div class="section">
        <div class="section-image">
            <img src="/images/goalicon2.png" alt="Goals Icon">
        </div>
        <h2>Goals</h2>
        <p>We aim to push the boundaries of technology to deliver solutions that enhance efficiency and reliability. Our goal is to support our clients in achieving their objectives by providing top-notch engineering solutions with unparalleled technical support.</p>
    </div>
    <div class="section">
        <div class="section-image">
            <img src="/images/offericon.png" alt="Offer Icon">
        </div>
        <h2>What We Offer</h2>
        <ul>
            <li><strong>Custom AI Solutions</strong>: Tailored AI solutions to meet your unique business needs, including capabilities such as Agent Orchestration, Visual Processing, Knowledge Base Development, and Fine-Tuning Models.</li>
            <li><strong>Engineering Services</strong>: Advanced engineering solutions to ensure robust project execution and system integration.</li>
            <li><strong>Consulting Services</strong>: Expert advice and strategies to optimize your IT infrastructure and operations.</li>
        </ul>
    </div>
    <div class="section">
        <div class="section-image">
            <img src="/images/expertiseicon.png" alt="Expertise Icon">
        </div>
        <h2>Our Expertise</h2>
        <ul>
            <li>Server Side Development: Microservices, containerization, database design, SQL/NoSQL, observability, and monitoring</li>
            <li>Programming Languages: Go, Python, TypeScript</li>
            <li>Data Management: Data backup, ETL, REST APIs, and backend development</li>
            <li>Databases: PostgreSQL, MongoDB, SQL Server, Redis</li>
            <li>DevOps: Infrastructure as code, CI/CD integration, high availability, cloud solutions (AWS/GCP)</li>
            <li>InfoSec: Application hardening, pen testing, security scans, and remediations</li>
            <li>MLOps: Deploy your machine learning models in production securely on-premise or in the cloud</li>
            <li>Front End Development: Single-page applications, UI frameworks, React, Next.js</li>
        </ul>
    </div>
    <div class="section">
        <div class="section-image">
            <img src="/images/experienceicon.png" alt="Experience Icon">
        </div>
        <h2>Experience</h2>
        <ul>
            <p>Our team has extensive experience working on diverse projects, such as:</p>
            <li>Developing a Go data backup application</li>
            <li>Enhancing search-and-rescue antenna configurations</li>
            <li>Implementing robust data processing systems</li>
            <li>Cloud-based project database at petabyte scale</li>
            <li>Multisite command and control software with hardware sensor integration</li>
            <li>On-demand cloud resourcing deployment</li>
        </ul>
    </div>

</div>

<footer>
    <p>At Exolvo, we are committed to excellence and innovation. <a href="/contact-form.html" style="color: inherit; text-decoration: underline;">Contact us</a> today to learn how we can help you achieve your goals.</p>
</footer>


</body>
</html>