---
title: "Consulting Services"
---

<style>
    .services-section {
        padding: 60px 20px;
    }

    .circle-image {
        width: 260px; /* Adjust the size to be smaller */
        height: 260px; /* Ensure the height matches the width for a perfect circle */
        border-radius: 50%; /* Make the image circular */
        object-fit: cover; /* Ensures the image covers the entire circle */
        display: block;
        margin: 20px auto; /* Center the image and add space above and below it */
    }

    .p{
        text-align: center;
    }

    .intro-text {
        font-size: 18px;
        color: #4C4F65;
        margin-bottom: 40px; /* Space after the intro text */
    }

    .intro-text h3 {
        font-size: 24px;
        color: #6A5ACD; /* Purple color for the section heading */
        margin-top: 40px; /* Space above the section heading */
        margin-bottom: 20px; /* Space below the section heading */
        text-align: center;
    }

    .service-title {
        background-color: #6A5ACD; /* Purple background for the title */
        color: white;
        padding: 15px 20px;
        font-size: 18px;
        cursor: pointer;
        text-align: left;
        border: none;
        outline: none;
        width: 100%;
        transition: background-color 0.3s ease;
        border-radius: 5px;
        margin-bottom: 5px;
    }

    .service-title:hover {
        background-color: #5a4dbd; /* Darker purple on hover */
    }

    .service-content {
        padding: 0 20px;
        background-color: #f4f9ff;
        max-height: 0;
        overflow: hidden;
        transition: max-height 0.3s ease-out;
        border-radius: 5px;
    }

    .service-content img {
        width: 100%;
        max-width: 600px; /* Adjust the max-width as needed */
        height: auto;
        margin: 15px 0; /* Add space around images */
        border-radius: 5px; /* Optional: Add a slight border radius */
    }

    .service-content p {
        margin: 15px 0;
        text-align: center;
    }

    .service-content ul {
        margin: 15px 0;
    }

    .active + .service-content {
        max-height: 1000px; /* Increased value to allow more content */
    }
</style>

<div class="services-section">
    <img src="/images/conult33.png" alt="Consulting Services Header Image" class="circle-image"> 
    <div class="intro-text">
        <p>Exolvo provides expert consulting services to help you optimize your IT infrastructure and operations. Our consultants offer strategic advice and practical solutions to enhance your technological capabilities and support your business goals.</p>
        <h3>Our Consulting Services</h3>
    </div>
    <button class="service-title">IT Infrastructure Optimization</button>
    <div class="service-content">
        <p>Enhancing the efficiency and reliability of your IT systems.</p>
    </div>
    <button class="service-title">Strategic Planning</button>
    <div class="service-content">
        <p>Providing insights and strategies to align technology with business objectives.</p>
    </div>
    <button class="service-title">Technical Advisory</button>
    <div class="service-content">
        <p>Offering expert advice on technology adoption, integration, and management.</p>
    </div>
    <div class="service-content">
        <p>At Exolvo, our goal is to provide you with the knowledge and tools needed to achieve success. Contact us today to learn more about our consulting services.</p>
    </div>
</div>

<script>
    document.addEventListener("DOMContentLoaded", function() {
        document.querySelectorAll('.service-title').forEach(button => {
            button.addEventListener('click', function () {
                this.classList.toggle('active');

                const content = this.nextElementSibling;
                if (this.classList.contains('active')) {
                    content.style.maxHeight = content.scrollHeight + 'px';
                } else {
                    content.style.maxHeight = null;
                }
            });
        });
    });
</script>

