<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>স্বপ্ন কম্পিউটার পয়েন্ট - আপনার ডিজিটাল সেবার নির্ভরযোগ্য ঠিকানা</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #3498db;
            --secondary-color: #2980b9;
            --accent-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #2c3e50;
            --success-color: #2ecc71;
            --font-primary: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            --font-bangla: 'SolaimanLipi', 'Siyam Rupali', Arial, sans-serif;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: var(--font-primary);
            line-height: 1.6;
            color: #333;
            background-color: #f5f5f5;
        }

        .bangla {
            font-family: var(--font-bangla);
        }

        /* Header Styles */
        header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .logo i {
            font-size: 2rem;
        }

        .logo-text h1 {
            font-size: 1.5rem;
            margin-bottom: 0.2rem;
        }

        .logo-text p {
            font-size: 0.8rem;
            opacity: 0.9;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 1.5rem;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s ease;
            padding: 0.5rem 0;
            position: relative;
        }

        nav ul li a:hover {
            opacity: 0.8;
        }

        nav ul li a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background-color: white;
            transition: width 0.3s ease;
        }

        nav ul li a:hover::after {
            width: 100%;
        }

        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            color: white;
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            background: url('https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
            position: relative;
            margin-top: 60px;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.6);
        }

        .hero-content {
            position: relative;
            z-index: 1;
            width: 100%;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .hero p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: 0 auto 2rem;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }

        .btn {
            display: inline-block;
            background-color: var(--accent-color);
            color: white;
            padding: 0.8rem 1.8rem;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
            border: none;
            cursor: pointer;
            font-size: 1rem;
        }

        .btn:hover {
            background-color: #c0392b;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }

        /* Services Section */
        .services {
            padding: 5rem 0;
            background-color: white;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3rem;
        }

        .section-title h2 {
            font-size: 2.5rem;
            color: var(--dark-color);
            margin-bottom: 1rem;
            position: relative;
            display: inline-block;
        }

        .section-title h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 3px;
            background-color: var(--primary-color);
        }

        .section-title p {
            color: #666;
            max-width: 700px;
            margin: 0 auto;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .service-card {
            background-color: var(--light-color);
            border-radius: 10px;
            overflow: hidden;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
        }

        .service-icon {
            background-color: var(--primary-color);
            color: white;
            font-size: 2.5rem;
            padding: 1.5rem;
            text-align: center;
        }

        .service-content {
            padding: 1.5rem;
        }

        .service-content h3 {
            font-size: 1.3rem;
            margin-bottom: 1rem;
            color: var(--dark-color);
        }

        .service-content ul {
            list-style-position: inside;
            margin-bottom: 1.5rem;
        }

        .service-content ul li {
            margin-bottom: 0.5rem;
            color: #555;
        }

        /* Features Section */
        .features {
            padding: 5rem 0;
            background-color: var(--light-color);
        }

        .features-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            align-items: center;
        }

        .features-image img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
        }

        .features-content h2 {
            font-size: 2.5rem;
            color: var(--dark-color);
            margin-bottom: 1.5rem;
        }

        .features-content p {
            color: #666;
            margin-bottom: 2rem;
        }

        .feature-item {
            display: flex;
            margin-bottom: 1.5rem;
        }

        .feature-icon {
            background-color: var(--primary-color);
            color: white;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
            margin-right: 1rem;
            flex-shrink: 0;
        }

        .feature-text h3 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
            color: var(--dark-color);
        }

        .feature-text p {
            color: #666;
            margin-bottom: 0;
        }

        /* Testimonials Section */
        .testimonials {
            padding: 5rem 0;
            background-color: white;
        }

        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .testimonial-card {
            background-color: var(--light-color);
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            position: relative;
        }

        .testimonial-card::before {
            content: '"';
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 5rem;
            color: rgba(52, 152, 219, 0.1);
            font-family: Georgia, serif;
            line-height: 1;
        }

        .testimonial-content {
            position: relative;
            z-index: 1;
            margin-bottom: 1.5rem;
            color: #555;
            font-style: italic;
        }

        .testimonial-author {
            display: flex;
            align-items: center;
        }

        .author-avatar {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            overflow: hidden;
            margin-right: 1rem;
        }

        .author-avatar img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .author-info h4 {
            font-size: 1.1rem;
            margin-bottom: 0.2rem;
            color: var(--dark-color);
        }

        .author-info p {
            color: #777;
            font-size: 0.9rem;
        }

        /* Contact Section */
        .contact {
            padding: 5rem 0;
            background-color: var(--light-color);
        }

        .contact-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 3rem;
        }

        .contact-info h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            color: var(--dark-color);
        }

        .contact-info p {
            color: #666;
            margin-bottom: 2rem;
        }

        .contact-details {
            margin-bottom: 2rem;
        }

        .contact-item {
            display: flex;
            align-items: flex-start;
            margin-bottom: 1.5rem;
        }

        .contact-icon {
            background-color: var(--primary-color);
            color: white;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1rem;
            margin-right: 1rem;
            flex-shrink: 0;
        }

        .contact-text h3 {
            font-size: 1.1rem;
            margin-bottom: 0.3rem;
            color: var(--dark-color);
        }

        .contact-text p, .contact-text a {
            color: #666;
            text-decoration: none;
        }

        .contact-text a:hover {
            color: var(--primary-color);
        }

        .social-links {
            display: flex;
            gap: 1rem;
        }

        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background-color: var(--primary-color);
            color: white;
            border-radius: 50%;
            transition: all 0.3s ease;
        }

        .social-links a:hover {
            background-color: var(--secondary-color);
            transform: translateY(-3px);
        }

        .contact-form .form-group {
            margin-bottom: 1.5rem;
        }

        .contact-form label {
            display: block;
            margin-bottom: 0.5rem;
            color: var(--dark-color);
            font-weight: 500;
        }

        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 0.8rem 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-family: inherit;
            font-size: 1rem;
            transition: all 0.3s ease;
        }

        .contact-form input:focus,
        .contact-form textarea:focus {
            outline: none;
            border-color: var(--primary-color);
            box-shadow: 0 0 0 3px rgba(52, 152, 219, 0.2);
        }

        .contact-form textarea {
            min-height: 150px;
            resize: vertical;
        }

        /* Footer */
        footer {
            background-color: var(--dark-color);
            color: white;
            padding: 3rem 0 1rem;
        }

        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .footer-col h3 {
            font-size: 1.3rem;
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 0.5rem;
        }

        .footer-col h3::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 50px;
            height: 2px;
            background-color: var(--primary-color);
        }

        .footer-col p {
            color: #bbb;
            margin-bottom: 1rem;
        }

        .footer-links {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 0.8rem;
        }

        .footer-links a {
            color: #bbb;
            text-decoration: none;
            transition: all 0.3s ease;
        }

        .footer-links a:hover {
            color: white;
            padding-left: 5px;
        }

        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #bbb;
            font-size: 0.9rem;
        }

        /* Responsive Styles */
        @media (max-width: 992px) {
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .hero p {
                font-size: 1.1rem;
            }
        }

        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            
            nav ul {
                margin-top: 1rem;
                justify-content: center;
            }
            
            nav ul li {
                margin: 0 0.8rem;
            }
            
            .hero h1 {
                font-size: 2.2rem;
            }
            
            .section-title h2 {
                font-size: 2rem;
            }
            
            .features-content h2 {
                font-size: 2rem;
            }
        }

        @media (max-width: 576px) {
            .mobile-menu-btn {
                display: block;
            }
            
            nav {
                position: fixed;
                top: 80px;
                left: -100%;
                width: 100%;
                background-color: var(--secondary-color);
                transition: all 0.3s ease;
                padding: 1rem 0;
            }
            
            nav.active {
                left: 0;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 0.5rem 0;
            }
            
            .hero {
                height: auto;
                padding: 6rem 0;
            }
            
            .hero h1 {
                font-size: 1.8rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
            
            .section-title h2 {
                font-size: 1.8rem;
            }
            
            .features-content h2 {
                font-size: 1.8rem;
            }
            
            .footer-container {
                grid-template-columns: 1fr;
            }
        }

        /* Animation */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .fade-in {
            animation: fadeIn 1s ease forwards;
        }

        .delay-1 {
            animation-delay: 0.2s;
        }

        .delay-2 {
            animation-delay: 0.4s;
        }

        .delay-3 {
            animation-delay: 0.6s;
        }

        .delay-4 {
            animation-delay: 0.8s;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container header-content">
            <div class="logo">
                <i class="fas fa-laptop-code"></i>
                <div class="logo-text">
                    <h1 class="bangla">স্বপ্ন কম্পিউটার পয়েন্ট</h1>
                    <p class="bangla">আপনার ডিজিটাল সেবার নির্ভরযোগ্য ঠিকানা</p>
                </div>
            </div>
            <button class="mobile-menu-btn" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </button>
            <nav id="mainNav">
                <ul>
                    <li><a href="#home" class="bangla">হোম</a></li>
                    <li><a href="#services" class="bangla">সেবাসমূহ</a></li>
                    <li><a href="#features" class="bangla">বিশেষত্ব</a></li>
                    <li><a href="#testimonials" class="bangla">গ্রাহক মতামত</a></li>
                    <li><a href="#contact" class="bangla">যোগাযোগ</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content container">
            <h1 class="fade-in bangla">🌟 স্বপ্ন কম্পিউটার পয়েন্ট - আপনার ডিজিটাল সেবার নির্ভরযোগ্য ঠিকানা! 🌟</h1>
            <p class="fade-in delay-1 bangla">বিশ্বস্ততা, গতি, এবং ১০০% নির্ভুলতার প্রতিশ্রুতি</p>
            <a href="#contact" class="btn fade-in delay-2 bangla">যোগাযোগ করুন</a>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="container">
            <div class="section-title">
                <h2 class="bangla">আমাদের সেবাসমূহ</h2>
                <p class="bangla">আমরা বিভিন্ন ধরনের ডিজিটাল সেবা প্রদান করে থাকি যা আপনার জীবনকে সহজ করবে</p>
            </div>
            <div class="services-grid">
                <!-- Passport Services -->
                <div class="service-card fade-in">
                    <div class="service-icon">
                        <i class="fas fa-passport"></i>
                    </div>
                    <div class="service-content">
                        <h3 class="bangla">🛂 পাসপোর্ট সংক্রান্ত সেবা</h3>
                        <ul class="bangla">
                            <li>নতুন পাসপোর্ট আবেদন</li>
                            <li>পাসপোর্ট রি-ইস্যু/নবায়ন</li>
                            <li>তথ্য সংশোধন (জন্ম তারিখ, নাম, ঠিকানা ইত্যাদি)</li>
                            <li>জরুরি (Urgent) পাসপোর্ট আবেদন</li>
                            <li>বিদেশ জন্মস্থান ও ঠিকানা মিল না থাকলেও আবেদন</li>
                        </ul>
                    </div>
                </div>

                <!-- NID Services -->
                <div class="service-card fade-in delay-1">
                    <div class="service-icon">
                        <i class="fas fa-id-card"></i>
                    </div>
                    <div class="service-content">
                        <h3 class="bangla">🆔 ভোটার ও জাতীয় পরিচয়পত্র (NID) সেবা</h3>
                        <ul class="bangla">
                            <li>নতুন ভোটার আবেদন</li>
                            <li>তথ্য সংশোধন (নাম, ঠিকানা, জন্ম তারিখ, ছবি ইত্যাদি)</li>
                            <li>অনলাইন NID কপি ডাউনলোড</li>
                            <li>NID পুনঃমুদ্রণ আবেদন</li>
                            <li>স্মার্ট কার্ড আবেদন ও সমস্যা সমাধান</li>
                        </ul>
                    </div>
                </div>

                <!-- Birth Registration -->
                <div class="service-card fade-in delay-2">
                    <div class="service-icon">
                        <i class="fas fa-baby"></i>
                    </div>
                    <div class="service-content">
                        <h3 class="bangla">👶 জন্ম নিবন্ধন সেবা</h3>
                        <ul class="bangla">
                            <li>নতুন জন্ম সনদ আবেদন</li>
                            <li>তথ্য সংশোধন (নাম, জন্মতারিখ, পিতামাতার নাম ইত্যাদি)</li>
                            <li>অনলাইন জন্ম সনদ ডাউনলোড</li>
                            <li>ইউনিয়ন/সিটি কর্পোরেশন তথ্য সংশোধন</li>
                        </ul>
                    </div>
                </div>

                <!-- Other Services -->
                <div class="service-card fade-in delay-3">
                    <div class="service-icon">
                        <i class="fas fa-file-alt"></i>
                    </div>
                    <div class="service-content">
                        <h3 class="bangla">📄 অন্যান্য গুরুত্বপূর্ণ সেবা</h3>
                        <ul class="bangla">
                            <li>পুলিশ ক্লিয়ারেন্স সার্টিফিকেট</li>
                            <li>টিন সার্টিফিকেট (TIN) নিবন্ধন ও সংশোধন</li>
                            <li>COVID-19 ভ্যাকসিন কার্ড ও সনদ ডাউনলোড</li>
                            <li>শিক্ষাগত সনদপত্র ডাউনলোড ও আবেদন</li>
                            <li>মার্কশিট/প্রবেশপত্র/অনলাইন ফর্ম পূরণ</li>
                            <li>চাকরির অনলাইন আবেদন ও রেজিস্ট্রেশন</li>
                            <li>ড্রাইভিং লাইসেন্স আবেদন (Learner/Permanent)</li>
                        </ul>
                    </div>
                </div>

                <!-- Printing Services -->
                <div class="service-card fade-in">
                    <div class="service-icon">
                        <i class="fas fa-print"></i>
                    </div>
                    <div class="service-content">
                        <h3 class="bangla">📁 প্রিন্টিং, স্ক্যানিং ও অন্যান্য</h3>
                        <ul class="bangla">
                            <li>রঙিন/সাদা-কালো প্রিন্ট</li>
                            <li>ছবি স্ক্যান ও পিডিএফ তৈরি</li>
                            <li>পাসপোর্ট সাইজ ছবি সম্পাদনা</li>
                            <li>ছবি ব্যাকগ্রাউন্ড রিমুভ</li>
                            <li>লেমিনেটিং, ফটোকপি, ডিজিটাল সাইন</li>
                        </ul>
                    </div>
                </div>

                <!-- Computer Services -->
                <div class="service-card fade-in delay-1">
                    <div class="service-icon">
                        <i class="fas fa-laptop"></i>
                    </div>
                    <div class="service-content">
                        <h3 class="bangla">🖥️ কম্পিউটার ও ইন্টারনেট সেবা</h3>
                        <ul class="bangla">
                            <li>MS Word, Excel, PowerPoint কাজ</li>
                            <li>অনলাইন ব্যাংক ড্রাফট</li>
                            <li>ইমেইল, ফর্ম ফিলআপ</li>
                            <li>সকল সরকারি ওয়েবসাইটে আবেদন</li>
                            <li>শিক্ষা বোর্ড, বীমা, ব্যাংক ফর্ম পূরণ</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features" id="features">
        <div class="container">
            <div class="section-title">
                <h2 class="bangla">আমাদের বিশেষত্ব</h2>
                <p class="bangla">আমরা কেন আপনার জন্য সেরা পছন্দ</p>
            </div>
            <div class="features-container">
                <div class="features-image fade-in">
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Dream Computer Point Features">
                </div>
                <div class="features-content">
                    <h2 class="bangla">🎯 আমাদের বিশেষত্ব:</h2>
                    <p class="bangla">আমরা আমাদের গ্রাহকদের জন্য সর্বোচ্চ মানের সেবা নিশ্চিত করি</p>
                    
                    <div class="feature-item fade-in delay-1">
                        <div class="feature-icon">
                            <i class="fas fa-bolt"></i>
                        </div>
                        <div class="feature-text">
                            <h3 class="bangla">দ্রুততম সময়ের মধ্যে কাজ</h3>
                            <p class="bangla">আমরা সবচেয়ে দ্রুততম সময়ে আপনার কাজ সম্পন্ন করি</p>
                        </div>
                    </div>
                    
                    <div class="feature-item fade-in delay-2">
                        <div class="feature-icon">
                            <i class="fas fa-check-circle"></i>
                        </div>
                        <div class="feature-text">
                            <h3 class="bangla">১০০% নির্ভুল ডেলিভারি</h3>
                            <p class="bangla">আমরা ভুলের জন্য কোন স্থান রাখি না, ১০০% নির্ভুলতা নিশ্চিত করি</p>
                        </div>
                    </div>
                    
                    <div class="feature-item fade-in delay-3">
                        <div class="feature-icon">
                            <i class="fas fa-user-friends"></i>
                        </div>
                        <div class="feature-text">
                            <h3 class="bangla">বন্ধুত্বপূর্ণ ব্যবহার</h3>
                            <p class="bangla">আমাদের গ্রাহক সেবা সবসময় বন্ধুত্বপূর্ণ এবং সহায়ক</p>
                        </div>
                    </div>
                    
                    <div class="feature-item fade-in delay-4">
                        <div class="feature-icon">
                            <i class="fas fa-lock"></i>
                        </div>
                        <div class="feature-text">
                            <h3 class="bangla">বিশ্বস্ত ও গোপনীয়তা রক্ষায় প্রতিশ্রুতিবদ্ধ</h3>
                            <p class="bangla">আপনার তথ্যের গোপনীয়তা আমরা সর্বোচ্চ গুরুত্ব দিয়ে থাকি</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials" id="testimonials">
        <div class="container">
            <div class="section-title">
                <h2 class="bangla">গ্রাহকদের মতামত</h2>
                <p class="bangla">আমাদের সেবা সম্পর্কে গ্রাহকরা কি বলছেন</p>
            </div>
            <div class="testimonials-grid">
                <div class="testimonial-card fade-in">
                    <div class="testimonial-content bangla">
                        আমি আমার পাসপোর্টের জন্য স্বপ্ন কম্পিউটার পয়েন্টের সেবা নিয়েছি। তারা অত্যন্ত দ্রুত এবং দক্ষতার সাথে আমার কাজটি সম্পন্ন করেছে। তাদের সেবা এবং ব্যবহার খুবই ভালো লেগেছে।
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Rahim Mia">
                        </div>
                        <div class="author-info">
                            <h4 class="bangla">রহিম মিয়া</h4>
                            <p class="bangla">ব্যবসায়ী</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card fade-in delay-1">
                    <div class="testimonial-content bangla">
                        NID সংশোধনের জন্য আমি অনেক জায়গায় গিয়েছিলাম, কিন্তু কোথাও কাজ হয়নি। শেষে স্বপ্ন কম্পিউটার পয়েন্টে আসি এবং তারা মাত্র ২ দিনের মধ্যে আমার সমস্যার সমাধান করে দেয়। ধন্যবাদ তাদেরকে।
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Fatema Begum">
                        </div>
                        <div class="author-info">
                            <h4 class="bangla">ফাতেমা বেগম</h4>
                            <p class="bangla">গৃহিণী</p>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card fade-in delay-2">
                    <div class="testimonial-content bangla">
                        আমি বিদেশে থাকি। আমার জন্ম নিবন্ধন সংশোধন করার প্রয়োজন ছিল। স্বপ্ন কম্পিউটার পয়েন্ট অনলাইনেই আমার সব কাজ সম্পন্ন করেছে। তাদের বিশ্বস্ততা এবং পেশাদারিত্ব দেখে আমি খুবই খুশি।
                    </div>
                    <div class="testimonial-author">
                        <div class="author-avatar">
                            <img src="https://randomuser.me/api/portraits/men/67.jpg" alt="Karim Uddin">
                        </div>
                        <div class="author-info">
                            <h4 class="bangla">করিম উদ্দিন</h4>
                            <p class="bangla">বিদেশ প্রবাসী</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <div class="section-title">
                <h2 class="bangla">যোগাযোগ করুন</h2>
                <p class="bangla">আমাদের সাথে যোগাযোগ করে আপনার প্রয়োজনীয় সেবা সম্পর্কে জানুন</p>
            </div>
            <div class="contact-container">
                <div class="contact-info fade-in">
                    <h2 class="bangla">📌 এখনই চলে আসুন</h2>
                    <p class="bangla">স্বপ্ন কম্পিউটার পয়েন্ট<br>💬 আপনি বলুন, আমরা কাজ করে দেব — একদম ঠিকমতো!</p>
                    
                    <div class="contact-details">
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div class="contact-text">
                                <h3 class="bangla">ঠিকানা</h3>
                                <p class="bangla">১২৩ কম্পিউটার মার্কেট, ৩য় তলা, ঢাকা</p>
                            </div>
                        </div>
                        
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-phone-alt"></i>
                            </div>
                            <div class="contact-text">
                                <h3 class="bangla">ফোন</h3>
                                <p><a href="tel:+8801712345678">+880 1712 345 678</a></p>
                                <p><a href="tel:+8801812345679">+880 1812 345 679</a></p>
                            </div>
                        </div>
                        
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div class="contact-text">
                                <h3 class="bangla">ইমেইল</h3>
                                <p><a href="mailto:info@dreamcomputerpoint.com">info@dreamcomputerpoint.com</a></p>
                            </div>
                        </div>
                        
                        <div class="contact-item">
                            <div class="contact-icon">
                                <i class="fas fa-clock"></i>
                            </div>
                            <div class="contact-text">
                                <h3 class="bangla">খোলার সময়</h3>
                                <p class="bangla">সকাল ৯টা - রাত ৯টা<br>শুক্রবার বন্ধ</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                
                <div class="contact-form fade-in delay-1">
                    <form id="contactForm">
                        <div class="form-group">
                            <label for="name" class="bangla">আপনার নাম</label>
                            <input type="text" id="name" name="name" required class="bangla">
                        </div>
                        
                        <div class="form-group">
                            <label for="phone" class="bangla">ফোন নম্বর</label>
                            <input type="tel" id="phone" name="phone" required>
                        </div>
                        
                        <div class="form-group">
                            <label for="email" class="bangla">ইমেইল (ঐচ্ছিক)</label>
                            <input type="email" id="email" name="email">
                        </div>
                        
                        <div class="form-group">
                            <label for="service" class="bangla">সেবা নির্বাচন করুন</label>
                            <select id="service" name="service" class="bangla" required>
                                <option value="" class="bangla">সেবা নির্বাচন করুন</option>
                                <option value="passport" class="bangla">পাসপোর্ট সংক্রান্ত সেবা</option>
                                <option value="nid" class="bangla">ভোটার ও NID সেবা</option>
                                <option value="birth" class="bangla">জন্ম নিবন্ধন সেবা</option>
                                <option value="other" class="bangla">অন্যান্য সেবা</option>
                            </select>
                        </div>
                        
                        <div class="form-group">
                            <label for="message" class="bangla">আপনার বার্তা</label>
                            <textarea id="message" name="message" required class="bangla"></textarea>
                        </div>
                        
                        <button type="submit" class="btn bangla">বার্তা পাঠান</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="footer-container">
                <div class="footer-col">
                    <h3 class="bangla">স্বপ্ন কম্পিউটার পয়েন্ট</h3>
                    <p class="bangla">আপনার ডিজিটাল সেবার নির্ভরযোগ্য ঠিকানা। আমরা বিশ্বস্ততা, গতি এবং নির্ভুলতার সাথে সকল ধরনের ডিজিটাল সেবা প্রদান করে থাকি।</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                
                <div class="footer-col">
                    <h3 class="bangla">গুরুত্বপূর্ণ লিংক</h3>
                    <ul class="footer-links">
                        <li><a href="#home" class="bangla">হোম</a></li>
                        <li><a href="#services" class="bangla">সেবাসমূহ</a></li>
                        <li><a href="#features" class="bangla">বিশেষত্ব</a></li>
                        <li><a href="#testimonials" class="bangla">গ্রাহক মতামত</a></li>
                        <li><a href="#contact" class="bangla">যোগাযোগ</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3 class="bangla">সেবাসমূহ</h3>
                    <ul class="footer-links">
                        <li><a href="#" class="bangla">পাসপোর্ট সেবা</a></li>
                        <li><a href="#" class="bangla">NID সেবা</a></li>
                        <li><a href="#" class="bangla">জন্ম নিবন্ধন</a></li>
                        <li><a href="#" class="bangla">প্রিন্টিং সেবা</a></li>
                        <li><a href="#" class="bangla">অনলাইন আবেদন</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h3 class="bangla">যোগাযোগ</h3>
                    <ul class="footer-links">
                        <li><i class="fas fa-map-marker-alt"></i> <span class="bangla">১২৩ কম্পিউটার মার্কেট, ৩য় তলা, ঢাকা</span></li>
                        <li><i class="fas fa-phone-alt"></i> <span>+880 1712 345 678</span></li>
                        <li><i class="fas fa-envelope"></i> <span>info@dreamcomputerpoint.com</span></li>
                        <li><i class="fas fa-clock"></i> <span class="bangla">সকাল ৯টা - রাত ৯টা (শুক্রবার বন্ধ)</span></li>
                    </ul>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p class="bangla">&copy; ২০২৩ স্বপ্ন কম্পিউটার পয়েন্ট। সকল স্বত্ব সংরক্ষিত।</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile Menu Toggle
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mainNav = document.getElementById('mainNav');
        
        mobileMenuBtn.addEventListener('click', () => {
            mainNav.classList.toggle('active');
            mobileMenuBtn.innerHTML = mainNav.classList.contains('active') ? 
                '<i class="fas fa-times"></i>' : '<i class="fas fa-bars"></i>';
        });
        
        // Smooth Scrolling for Anchor Links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                if(mainNav.classList.contains('active')) {
                    mainNav.classList.remove('active');
                    mobileMenuBtn.innerHTML = '<i class="fas fa-bars"></i>';
                }
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                window.scrollTo({
                    top: targetElement.offsetTop - 80,
                    behavior: 'smooth'
                });
            });
        });
        
        // Form Submission
        const contactForm = document.getElementById('contactForm');
        
        contactForm.addEventListener('submit', (e) => {
            e.preventDefault();
            
            // Get form values
            const name = document.getElementById('name').value;
            const phone = document.getElementById('phone').value;
            const email = document.getElementById('email').value;
            const service = document.getElementById('service').value;
            const message = document.getElementById('message').value;
            
            // Here you would typically send the data to a server
            // For this example, we'll just show an alert
            alert(`ধন্যবাদ ${name}! আপনার বার্তা পেয়েছি। আমরা শীঘ্রই আপনার সাথে যোগাযোগ করব।`);
            
            // Reset form
            contactForm.reset();
        });
        
        // Animation on Scroll
        const fadeElements = document.querySelectorAll('.fade-in');
        
        const fadeInOnScroll = () => {
            fadeElements.forEach(element => {
                const elementTop = element.getBoundingClientRect().top;
                const windowHeight = window.innerHeight;
                
                if(elementTop < windowHeight - 100) {
                    element.style.opacity = '1';
                    element.style.transform = 'translateY(0)';
                }
            });
        };
        
        // Initialize elements as invisible
        fadeElements.forEach(element => {
            element.style.opacity = '0';
            element.style.transform = 'translateY(20px)';
            element.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
        });
        
        // Check on scroll and on load
        window.addEventListener('scroll', fadeInOnScroll);
        window.addEventListener('load', fadeInOnScroll);
    </script>
</body>
</html>
