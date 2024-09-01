<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Products - Exolvo</title>
    <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        color: #333;
        background: linear-gradient(to bottom right, #000000 0%, #000000 100%); /* Black gradient */
        height: 100vh; /* Ensures the gradient covers the full height of the viewport */
    }
    .container {
        max-width: 1200px;
        margin: auto;
        padding: 20px;
        background: #fff; /* Solid white for content areas */
        box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Adds depth to content sections */
    }
    .header {
        background: linear-gradient(135deg, #9C8FC7 0%, #6A5ACD 100%); /* Match the button gradient */
        padding: 40px 20px;
        text-align: center;
        color: #ffffff;
        border-radius: 15px; /* Rounded corners */
    }
    .intro {
        background: url('/images/procket.png') no-repeat center;
        background-size: cover;
        text-align: center;
        padding: 100px 20px;
        color: #F06105;
        font-weight: bold;
        border-radius: 15px;
        margin: 20px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    .intro p {
    font-size: 24px;
    margin-top: 0;
    max-width: 800px;
    margin-left: auto;
    margin-right: auto;
    color: #FFFFFF; /* Match the text color to the one in the Engineering Services section */
    font-weight: normal; /* Match the font weight */
    }
    .intro a {
    display: inline-block;
    padding: 10px 20px;
    background: linear-gradient(135deg, #9C8FC7 0%, #6A5ACD 100%); /* Match the button gradient */
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    margin-top: 20px;
    }
    .product {
        display: flex;
        align-items: center;
        margin-bottom: 20px;
        padding: 20px;
        background: #fff; /* Keeps product cards white */
        border-radius: 8px; /* Adds rounded corners to product cards */
    }
    .product img {
        width: 300px;
        margin-right: 20px;
    }
    .product.reverse {
        flex-direction: row-reverse;
    }
    .product p {
        flex: 1;
    }
    .product a {
    padding: 10px 20px;
    background: linear-gradient(135deg, #9C8FC7 0%, #6A5ACD 100%); /* Gradient from light purple to a slightly darker purple */
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    }
</style>

</head>
<body>

<div class="header">
    <h1>Exolvo Products</h1>
    <p>Bringing Software Engineering to ML Deployments</p>
</div>

<div class="intro">
    <p>Explore our innovative solutions crafted to enhance your business operations. Our tools and services are designed to bring precision and efficiency, enabling your team to achieve outstanding results with cutting-edge technology. Dive into our range of offerings to find exactly what your business needs to thrive in a competitive landscape.</p>
    <a href="#detailed">Learn More</a>
</div>

<div class="container" id="detailed">
    <div class="product">
        <img src="/images/engi1.png" alt="Engineering Services">
        <div>
            <h2>Engineering Services</h2>
            <p>We offer a wide range of engineering services to help you build and maintain your applications, including Full Stack Development, DevOps, MLOps, and InfoSec.</p>
            <a href="/products/engineering-solutions/">Learn More</a>
        </div>
    </div>
    <div class="product reverse">
        <img src="/images/conult33.png" alt="Consulting Services">
        <div>
            <h2>Consulting Services</h2>
            <p>Our Consulting Services provide expert advice and strategies to optimize your IT infrastructure and operations, ensuring efficiency and scalability.</p>
            <a href="/products/consult-solutions/">Learn More</a>
        </div>
    </div>
    <div class="product">
        <img src="/images/aibra1.png" alt="AI Solutions">
        <div>
            <h2>AI Solutions</h2>
            <p>Our AI Solutions offer cutting-edge tools designed to enhance tactical coordination and data processing capabilities.</p>
            <a href="/products/ai-solutions/">Learn More</a>
        </div>
    </div>
</div>

</body>
</html>