<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valerie Sullivan - Licensed Cosmetologist</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background: #e0aaff;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            position: relative;
            overflow: hidden;
        }
        header::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('sparkle.gif') repeat;
            opacity: 0.3;
            pointer-events: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
        }
        h2 {
            color: #d953c6;
        }
        .services img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .contact-info {
            background: #f4f4f4;
            padding: 10px;
            border-radius: 10px;
        }
        footer {
            background: #e0aaff;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .button {
            display: inline-block;
            background: #d953c6;
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin: 10px 0;
        }
        .button:hover {
            background: #b93e8c;
        }
    </style>
</head>
<body>
    <header>
        Valerie Sullivan - Licensed Cosmetologist
    </header>
    <div class="container">
        <section class="about-me">
            <h2>About Me</h2>
            <p>Hello! I'm Valerie Sullivan, a Licensed Cosmetologist dedicated to making you look and feel fabulous. With years of experience in the industry, I offer a range of services tailored to your needs. My passion is to bring out the best in you through personalized beauty solutions.</p>
        </section>

        <section class="services">
            <h2>Services I Offer</h2>
            <p>Explore the variety of services I provide, each designed to meet your unique style and preference. From elegant hairstyles to professional makeup, I ensure top-notch quality and satisfaction.</p>
            <div>
                <h3>Hair Styling</h3>
                <p>Beautiful and trendy haircuts and styles.</p>
                <h3>Makeup Artistry</h3>
                <p>Professional makeup for any occasion.</p>
                <h3>Nail Care</h3>
                <p>Manicures and pedicures with a touch of glam.</p>
            </div>
        </section>

        <section class="photos">
            <h2>Look Book</h2>
            <p>Here are some examples of my work. Click on the images to view them in detail.</p>
            <img src="example1.jpg" alt="Example Work 1">
            <img src="example2.jpg" alt="Example Work 2">
            <img src="example3.jpg" alt="Example Work 3">
        </section>

        <section class="booking-contact">
            <h2>Booking & Contact Information</h2>
            <p>To book an appointment, please contact me via email or phone. I am available for consultations and sessions at the following times:</p>
            <div class="contact-info">
                <p><strong>Email:</strong> valerie@example.com</p>
                <p><strong>Phone:</strong> (123) 456-7890</p>
                <p><strong>Working Days:</strong> Monday - Friday</p>
                <p><strong>Working Hours:</strong> 9:00 AM - 6:00 PM</p>
                <a href="mailto:valerie@example.com" class="button">Book Now</a>
            </div>
        </section>

        <section class="aftercare">
            <h2>After Care Advice</h2>
            <p>To ensure your beauty treatments last longer, follow these aftercare tips:</p>
            <ul>
                <li>Avoid washing your hair for 24-48 hours after styling.</li>
                <li>Use gentle, sulfate-free shampoo and conditioner.</li>
                <li>Moisturize your skin regularly to keep your glow.</li>
            </ul>
        </section>

        <section class="products">
            <h2>Recommended Products</h2>
            <p>Enhance your beauty routine with these amazing products:</p>
            <ul>
                <li><strong>Shampoo:</strong> Brand XYZ</li>
                <li><strong>Conditioner:</strong> Brand ABC</li>
                <li><strong>Styling Gel:</strong> Brand DEF</li>
            </ul>
        </section>
    </div>

    <footer>
        &copy; 2024 Valerie Sullivan. All rights reserved.
    </footer>
</body>
</html>
