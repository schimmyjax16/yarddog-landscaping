<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YardDog Landscaping | Professional Lawn Care & Design</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            line-height: 1.6;
            color: #333;
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        img {
            max-width: 100%;
        }
        .btn {
            display: inline-block;
            background: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
        .btn:hover {
            background: #45a049;
        }

        /* Header & Hero */
        header {
            background: #4CAF50;
            color: white;
            padding: 20px 0;
        }
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
        }
        nav ul {
            display: flex;
            list-style: none;
        }
        nav ul li {
            margin-left: 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1600566752225-555b5afcd839?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
            height: 60vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
        }
        .hero-content {
            position: relative;
            z-index: 1;
            width: 100%;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        /* Sections */
        section {
            padding: 60px 0;
        }
        .section-title {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2rem;
            color: #4CAF50;
        }

        /* Services */
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .service-card {
            border: 1px solid #ddd;
            padding: 20px;
            border-radius: 5px;
            text-align: center;
        }
        .service-card img {
            border-radius: 5px;
            margin-bottom: 15px;
            height: 200px;
            object-fit: cover;
        }
        .service-schedule {
            background: #f9f9f9;
            padding: 30px;
            border-radius: 5px;
            margin-top: 40px;
        }
        .service-schedule h3 {
            color: #4CAF50;
            margin-bottom: 15px;
        }
        .service-schedule ul {
            list-style-type: none;
        }
        .service-schedule li {
            margin-bottom: 8px;
            position: relative;
            padding-left: 20px;
        }
        .service-schedule li:before {
            content: "•";
            color: #4CAF50;
            position: absolute;
            left: 0;
        }

        /* Vision (Replaced Testimonials) */
        .vision {
            background: #f9f9f9;
            text-align: center;
        }
        .vision p {
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.1rem;
        }
        .vision .highlight {
            color: #4CAF50;
            font-weight: bold;
        }

        /* Contact */
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }
        .form-group {
            margin-bottom: 20px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .form-group textarea {
            height: 150px;
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }
        .manager-info {
            margin-top: 20px;
            padding: 15px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 5px;
        }
        .manager-info p {
            margin: 5px 0;
        }
        .manager-info a {
            color: #4CAF50;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <nav>
                <div class="logo">YardDog Landscaping</div>
                <ul>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#vision">Vision</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content container">
            <h1>Transform Your Outdoor Space</h1>
            <p>Professional landscaping services tailored to your needs.</p>
            <a href="#contact" class="btn">Get a Free Quote</a>
        </div>
    </section>

    <!-- Services -->
    <section id="services" class="container">
        <h2 class="section-title">Our Services</h2>
        <div class="services">
            <div class="service-card">
                <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Lawn Care">
                <h3>Lawn Care</h3>
                <p>Mowing, fertilizing, and weed control to keep your lawn lush and green.</p>
            </div>
            <div class="service-card">
                <img src="https://images.unsplash.com/photo-1585320806297-9794b3e4eeae?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Landscape Design">
                <h3>Landscape Design</h3>
                <p>Custom designs to enhance your property's beauty and functionality.</p>
            </div>
            <div class="service-card">
                <img src="https://images.unsplash.com/photo-1476231682828-37e571bc172f?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Tree & Shrub Care">
                <h3>Tree & Shrub Care</h3>
                <p>Pruning, trimming, and disease management for healthy plants.</p>
            </div>
        </div>

        <!-- Service Area & Hours -->
        <div class="service-schedule">
            <h3>Service Areas & Operating Hours</h3>
            <p><strong>Cities we serve:</strong> Prior Lake, Lakeville, Burnsville, Eagan, Apple Valley</p>
            <p><strong>Always available:</strong> 9AM - 9PM</p>
            <ul>
                <li><strong>Monday:</strong> Prior Lake & Burnsville</li>
                <li><strong>Tuesday:</strong> Burnsville & Eagan</li>
                <li><strong>Wednesday:</strong> Eagan & Apple Valley</li>
                <li><strong>Thursday:</strong> Apple Valley & Lakeville</li>
                <li><strong>Friday:</strong> Lakeville & Prior Lake</li>
                <li><strong>Saturday & Sunday:</strong> Big projects or extras</li>
            </ul>
        </div>
    </section>

    <!-- About -->
    <section id="about" class="container">
        <h2 class="section-title">About YardDog</h2>
        <p>Hi, I'm Jaxson Schermerhorn—a high school student with a passion for transforming outdoor spaces. 
           I started YardDog Landscaping to provide affordable, quality services while learning the ropes of entrepreneurship. 
           My mission? To deliver <strong>reliable, detail-oriented work</strong> that makes your property shine, whether it's a backyard 
           or a commercial space. Every project is a chance to grow (both your lawn and my business!).</p>
    </section>

    <!-- Vision (Replaced Testimonials) -->
    <section id="vision" class="vision">
        <div class="container">
            <h2 class="section-title">Our Vision</h2>
            <p><span class="highlight">YardDog's Promise:</span> We take pride in treating every lawn like it's our own. 
               From precise mowing patterns to eco-friendly practices, we commit to <strong>quality, transparency, and hustle</strong>. 
               As a young business, we're building trust one satisfied customer at a time—because your yard deserves 
               the best, no matter the size of our company.</p>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="container">
        <h2 class="section-title">Contact Us</h2>
        <div class="contact-form">
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="phone">Phone</label>
                    <input type="tel" id="phone" name="phone">
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" required></textarea>
                </div>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2025 YardDog Landscaping. All rights reserved.</p>
            <p>Prior Lake, Minnesota</p>
            
            <!-- Manager Contact Section -->
            <div class="manager-info">
                <p><strong>Business Manager</strong></p>
                <p>Jaxson Schermerhorn</p>
                <p>Phone: <a href="tel:763-321-0536">763-321-0536</a></p>
                <p>Email: <a href="mailto:schermerhornjaxson@gmail.com">schermerhornjaxson@gmail.com</a></p>
            </div>
        </div>
    </footer>
</body>
</html>
