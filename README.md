<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dibrugarh University Computer Education Centre</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #fff;
            color: #333;
            text-align: left;
            padding: 1rem;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
        }
        header img {
            max-width: 100%;
            height: auto;
        }
        .contact {
            text-align: right;
            color: #333;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
        }
        .contact h2, .contact p {
            margin: 0 15px 0 0;
        }
        nav {
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 0;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-evenly;
        }
        nav ul li {
            margin: 5px;
        }
        nav ul li a {
            display: block;
            padding: 10px 15px;
            text-decoration: none;
            color: #fff;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        nav ul li a:hover {
            background-color: rgba(255, 255, 255, 0.2);
        }
        main {
            padding: 30px;
        }
        .course {
            border: 1px solid #ddd;
            margin-bottom: 30px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 5px;
        }
        .course h3 {
            color: #4CAF50;
            font-weight: bold;
        }
        #imageSlider {
            width: 100%;
            max-width: 1000px;
            margin: 0 auto;
            overflow: hidden;
        }
        .slider-wrapper {
            display: flex;
            transition: transform 0.5s ease;
        }
        .slider-wrapper img {
            width: 100%;
            height: auto;
        }
        #paymentOptions {
            text-align: center;
            margin-top: 40px;
        }
        .payment-button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin: 10px;
            font-size: 1em;
        }
        .payment-button:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 40px 20px;
        }
        .footer-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            max-width: 1200px;
            margin: 0 auto;
        }
        .footer-section {
            flex: 1;
            min-width: 200px;
            margin-bottom: 20px;
        }
        .footer-section h3 {
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }
        .footer-section ul {
            list-style-type: none;
            padding: 0;
        }
        .footer-section ul li {
            margin-bottom: 10px;
        }
        .footer-bottom {
            text-align: center;
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid #555;
        }
        @media (max-width: 768px) {
            header, .contact, nav ul {
                flex-direction: column;
                align-items: center;
            }
            .contact h2, .contact p {
                margin: 5px 0;
            }
            .footer-section {
                flex-basis: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <div>
            <img src="https://dibru.ac.in/wp-content/uploads/2024/03/DUNEW-new-logo-scaled.jpg" alt="Dibrugarh University Logo">
        </div>
        <div class="contact">
            <h2>Email:</h2>
            <p><a href="mailto:dceoffice.gov@gmail.com">dceoffice.gov@gmail.com</a></p>
            <h2>Call Us:</h2>
            <p><a href="tel:+919365430379">+91 9365430379</a></p>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#courses">Courses</a></li>
            <li><a href="#branches">Branches</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#franchise">Apply for Franchise</a></li>
            <li><a href="#verification">Student Verification</a></li>
            <li><a href="#contact">Contact Us</a></li>
            <li><a href="#result">Result</a></li>
        </ul>
    </nav>

    <section id="imageSlider">
        <div class="slider-wrapper">
            <img src="https://via.placeholder.com/1000x400/0000FF/808080?text=Image+1" alt="Image 1">
            <img src="https://via.placeholder.com/1000x400/FF0000/FFFFFF?text=Image+2" alt="Image 2">
            <img src="https://via.placeholder.com/1000x400/00FF00/000000?text=Image+3" alt="Image 3">
            <img src="https://via.placeholder.com/1000x400/FFFF00/000000?text=Image+4" alt="Image 4">
            <img src="https://via.placeholder.com/1000x400/00FFFF/000000?text=Image+5" alt="Image 5">
            <img src="https://via.placeholder.com/1000x400/FF00FF/000000?text=Image+6" alt="Image 6">
        </div>
    </section>

    <main>
        <section id="courses">
            <h2 style="color:#4CAF50;">COURSES OFFERED</h2>
            <div class="course">
                <h3>DCA (Diploma in Computer Applications)</h3>
                <p>Eligibility: 10th</p>
                <p>Semesters: 2</p>
                <p>Duration: 12 Months</p>
                <p>Semester I: Fundamental of Computer, OS (DOS, Windows 7), MS-Office (Word, Excel, PowerPoint), Computer Network, Visual Basic Intro.</p>
                <p>Semester II: HTML, Tally, DTP (Pagemaker, Corel Draw, Photoshop).</p>
            </div>
            <!-- Other courses... -->
        </section>
    </main>

    <div id="paymentOptions">
        <button class="payment-button" onclick="payWithRazorpay()">Pay with Razorpay</button>
        <button class="payment-button" onclick="payWithUPI()">Pay with UPI</button>
    </div>

    <footer>
        <div class="footer-content">
            <div class="footer-section">
                <h3>ABOUT US</h3>
                <p>Dibrugarh University Computer Education Centre is committed to providing quality education in computer science and applications. We offer a range of courses designed to meet the evolving needs of the IT industry.</p>
            </div>
            <div class="footer-section">
                <h3>COURSES</h3>
                <ul>
                    <li>DCA (Diploma in Computer Applications)</li>
                    <li>ADCA (Advanced Diploma in Computer Applications)</li>
                    <li>BCA (Bachelor of Computer Applications)</li>
                    <li>DIA (Diploma in Information Applications)</li>
                    <li>More courses available...</li>
                </ul>
            </div>
            <div class="footer-section">
                <h3>QUICK LINKS</h3>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About Us</a></li>
                    <li><a href="#courses">Courses</a></li>
                    <li><a href="#contact">Contact Us</a></li>
                    <li><a href="#result">Results</a></li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p>©️ Dibrugarh University. All rights reserved | Designed by Student of University</p>
        </div>
    </footer>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.10.4/gsap.min.js"></script>
    <script>
        const sliderWrapper = document.querySelector('.slider-wrapper');
        let currentSlide = 0;
        const totalSlides = document.querySelectorAll('.slider-wrapper img').length;

        function slideImages() {
            currentSlide = (currentSlide + 1) % totalSlides;
            gsap.to(sliderWrapper, {
                x: -(currentSlide * 100) + '%',
                duration: 1.5,
                ease: 'power2.inOut'
            });
        }

        setInterval(slideImages, 3000);

        function payWithRazorpay() {
            alert("Razorpay payment feature to be implemented");
        }

        function payWithUPI() {
            alert("UPI payment feature to be implemented");
        }
    </script>
</body>
</html>
