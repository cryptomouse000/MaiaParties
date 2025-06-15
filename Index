<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Magical Moments - Children's Entertainment | Sutton Coldfield</title>
    <meta name="description" content="Professional children's entertainer in Sutton Coldfield & Birmingham. Disney characters, singing, party games for kids birthdays & events.">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #ff6b6b;
            --secondary: #4ecdc4;
            --accent: #ffe66d;
            --purple: #a8e6cf;
            --dark: #2c3e50;
            --light: #ecf0f1;
            --white: #ffffff;
            --shadow: rgba(0, 0, 0, 0.1);
            --gradient-1: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            --gradient-2: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
            --gradient-3: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
        }

```
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: 'Poppins', sans-serif;
        line-height: 1.7;
        color: var(--dark);
        overflow-x: hidden;
    }

    .container {
        max-width: 1400px;
        margin: 0 auto;
        padding: 0 2rem;
    }

    /* Navigation */
    .navbar {
        position: fixed;
        top: 0;
        width: 100%;
        background: rgba(255, 255, 255, 0.95);
        backdrop-filter: blur(20px);
        z-index: 1000;
        padding: 1rem 0;
        transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        border-bottom: 1px solid rgba(255, 255, 255, 0.1);
    }

    .nav-content {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .logo {
        font-size: 1.75rem;
        font-weight: 700;
        background: var(--gradient-2);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }

    .nav-links {
        display: flex;
        list-style: none;
        gap: 2.5rem;
    }

    .nav-links a {
        text-decoration: none;
        color: var(--dark);
        font-weight: 500;
        font-size: 0.95rem;
        transition: all 0.3s ease;
        position: relative;
    }

    .nav-links a::after {
        content: '';
        position: absolute;
        bottom: -5px;
        left: 0;
        width: 0;
        height: 2px;
        background: var(--primary);
        transition: width 0.3s ease;
    }

    .nav-links a:hover::after {
        width: 100%;
    }

    /* Hero Section */
    .hero {
        min-height: 100vh;
        background: var(--gradient-1);
        display: flex;
        align-items: center;
        position: relative;
        overflow: hidden;
    }

    .hero::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" patternUnits="userSpaceOnUse" width="100" height="100"><circle cx="25" cy="25" r="1" fill="rgba(255,255,255,0.1)"/><circle cx="75" cy="75" r="1.5" fill="rgba(255,255,255,0.08)"/><circle cx="50" cy="10" r="0.8" fill="rgba(255,255,255,0.12)"/></pattern></defs><rect width="100%" height="100%" fill="url(%23grain)"/></svg>') repeat;
        opacity: 0.3;
    }

    .hero-content {
        position: relative;
        z-index: 2;
        color: white;
        max-width: 800px;
    }

    .hero h1 {
        font-size: clamp(3rem, 8vw, 6rem);
        font-weight: 800;
        line-height: 1.1;
        margin-bottom: 1.5rem;
        background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }

    .hero .subtitle {
        font-size: clamp(1.1rem, 3vw, 1.4rem);
        font-weight: 400;
        margin-bottom: 3rem;
        opacity: 0.9;
        letter-spacing: 0.5px;
    }

    .cta-button {
        display: inline-flex;
        align-items: center;
        gap: 0.5rem;
        background: var(--white);
        color: var(--dark);
        padding: 1rem 2.5rem;
        font-size: 1.1rem;
        font-weight: 600;
        border: none;
        border-radius: 50px;
        cursor: pointer;
        transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        text-decoration: none;
        box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
    }

    .cta-button:hover {
        transform: translateY(-3px);
        box-shadow: 0 25px 50px rgba(0, 0, 0, 0.2);
    }

    .hero-visual {
        position: absolute;
        right: -10%;
        top: 50%;
        transform: translateY(-50%);
        width: 600px;
        height: 600px;
        opacity: 0.1;
    }

    .floating-shapes {
        position: absolute;
        width: 100%;
        height: 100%;
        overflow: hidden;
    }

    .shape {
        position: absolute;
        border-radius: 50%;
        background: rgba(255, 255, 255, 0.1);
        animation: float 20s infinite linear;
    }

    .shape:nth-child(1) { width: 80px; height: 80px; top: 20%; left: 10%; animation-delay: 0s; }
    .shape:nth-child(2) { width: 120px; height: 120px; top: 60%; right: 15%; animation-delay: 7s; }
    .shape:nth-child(3) { width: 60px; height: 60px; bottom: 30%; left: 20%; animation-delay: 14s; }

    @keyframes float {
        0% { transform: translateY(0px) rotate(0deg); opacity: 0.1; }
        50% { transform: translateY(-100px) rotate(180deg); opacity: 0.3; }
        100% { transform: translateY(0px) rotate(360deg); opacity: 0.1; }
    }

    /* Sections */
    .section {
        padding: 8rem 0;
    }

    .section-header {
        text-align: center;
        margin-bottom: 5rem;
    }

    .section-title {
        font-size: clamp(2.5rem, 5vw, 3.5rem);
        font-weight: 700;
        margin-bottom: 1rem;
        background: var(--gradient-2);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }

    .section-subtitle {
        font-size: 1.2rem;
        color: #666;
        max-width: 600px;
        margin: 0 auto;
    }

    /* Services */
    .services {
        background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
    }

    .service-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
        gap: 2.5rem;
    }

    .service-card {
        background: var(--white);
        padding: 3rem 2rem;
        border-radius: 20px;
        box-shadow: 0 20px 60px rgba(0, 0, 0, 0.05);
        transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        position: relative;
        overflow: hidden;
    }

    .service-card::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        height: 4px;
        background: var(--gradient-2);
    }

    .service-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 30px 80px rgba(0, 0, 0, 0.1);
    }

    .service-icon {
        width: 80px;
        height: 80px;
        margin: 0 auto 2rem;
        background: var(--gradient-3);
        border-radius: 20px;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 2rem;
    }

    .service-card h3 {
        font-size: 1.5rem;
        font-weight: 600;
        margin-bottom: 1rem;
        text-align: center;
        color: var(--dark);
    }

    .service-card p {
        color: #666;
        text-align: center;
        line-height: 1.6;
    }

    /* About */
    .about {
        background: var(--white);
    }

    .about-content {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 5rem;
        align-items: center;
    }

    .about-text h2 {
        font-size: 2.5rem;
        font-weight: 700;
        margin-bottom: 2rem;
        color: var(--dark);
    }

    .about-text p {
        font-size: 1.1rem;
        color: #666;
        margin-bottom: 1.5rem;
        line-height: 1.7;
    }

    .about-visual {
        background: var(--gradient-3);
        height: 400px;
        border-radius: 20px;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 4rem;
        color: white;
        position: relative;
        overflow: hidden;
    }

    .about-visual::before {
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="20" cy="20" r="2" fill="rgba(255,255,255,0.2)"/><circle cx="80" cy="80" r="3" fill="rgba(255,255,255,0.1)"/><circle cx="50" cy="50" r="1" fill="rgba(255,255,255,0.3)"/></svg>') repeat;
    }

    /* Testimonials */
    .testimonials {
        background: linear-gradient(135deg, #ffecd2 0%, #fcb69f 100%);
    }

    .testimonial-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 2.5rem;
    }

    .testimonial {
        background: var(--white);
        padding: 2.5rem;
        border-radius: 20px;
        box-shadow: 0 20px 60px rgba(0, 0, 0, 0.05);
        transition: transform 0.3s ease;
    }

    .testimonial:hover {
        transform: translateY(-5px);
    }

    .stars {
        color: #ffd700;
        font-size: 1.5rem;
        margin-bottom: 1.5rem;
    }

    .testimonial p {
        font-size: 1rem;
        color: #666;
        line-height: 1.6;
        margin-bottom: 1.5rem;
        font-style: italic;
    }

    .testimonial strong {
        color: var(--dark);
        font-weight: 600;
    }

    /* Contact */
    .contact {
        background: var(--gradient-1);
        color: white;
    }

    .contact .section-title {
        background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
    }

    .contact .section-subtitle {
        color: rgba(255, 255, 255, 0.8);
    }

    .contact-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 2rem;
    }

    .contact-card {
        background: rgba(255, 255, 255, 0.1);
        backdrop-filter: blur(20px);
        padding: 2.5rem 2rem;
        border-radius: 20px;
        text-align: center;
        border: 1px solid rgba(255, 255, 255, 0.1);
        transition: transform 0.3s ease;
    }

    .contact-card:hover {
        transform: translateY(-5px);
    }

    .contact-icon {
        width: 60px;
        height: 60px;
        margin: 0 auto 1.5rem;
        background: rgba(255, 255, 255, 0.2);
        border-radius: 15px;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 1.5rem;
    }

    .contact-card h3 {
        font-size: 1.3rem;
        font-weight: 600;
        margin-bottom: 1rem;
    }

    .contact-card p {
        opacity: 0.9;
        line-height: 1.5;
    }

    .contact-cta {
        text-align: center;
        margin-top: 4rem;
    }

    .contact-cta .cta-button {
        background: var(--white);
        color: var(--dark);
    }

    /* Mobile Menu */
    .mobile-menu {
        display: none;
        background: none;
        border: none;
        font-size: 1.5rem;
        cursor: pointer;
        color: var(--dark);
    }

    /* Responsive */
    @media (max-width: 768px) {
        .container {
            padding: 0 1rem;
        }

        .nav-links {
            display: none;
        }

        .mobile-menu {
            display: block;
        }

        .hero {
            text-align: center;
            padding: 2rem 0;
        }

        .hero-visual {
            display: none;
        }

        .about-content {
            grid-template-columns: 1fr;
            gap: 3rem;
        }

        .section {
            padding: 5rem 0;
        }

        .service-grid,
        .testimonial-grid,
        .contact-grid {
            grid-template-columns: 1fr;
        }
    }

    /* Smooth animations */
    .fade-in {
        opacity: 0;
        transform: translateY(30px);
        transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
    }

    .fade-in.visible {
        opacity: 1;
        transform: translateY(0);
    }
</style>
```

</head>
<body>
    <nav class="navbar">
        <div class="container">
            <div class="nav-content">
                <div class="logo">Magical Moments</div>
                <ul class="nav-links">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#testimonials">Reviews</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
                <button class="mobile-menu">☰</button>
            </div>
        </div>
    </nav>

```
<section id="home" class="hero">
    <div class="floating-shapes">
        <div class="shape"></div>
        <div class="shape"></div>
        <div class="shape"></div>
    </div>
    <div class="container">
        <div class="hero-content">
            <h1>Bringing Disney Magic to Life</h1>
            <p class="subtitle">Professional children's entertainment in Sutton Coldfield & Birmingham. Authentic Disney characters, interactive shows, and unforgettable party experiences.</p>
            <a href="#contact" class="cta-button">
                Book Your Party
                <span>✨</span>
            </a>
        </div>
    </div>
</section>

<section id="services" class="services section">
    <div class="container">
        <div class="section-header fade-in">
            <h2 class="section-title">Our Services</h2>
            <p class="section-subtitle">Creating magical moments with professional entertainment tailored for young children</p>
        </div>
        <div class="service-grid">
            <div class="service-card fade-in">
                <div class="service-icon">👸</div>
                <h3>Disney Character Visits</h3>
                <p>Authentic Disney princess and character performances with professional costumes and engaging storytelling that brings beloved characters to life.</p>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">🎵</div>
                <h3>Interactive Shows</h3>
                <p>Sing-along sessions and dance performances featuring all the classic Disney songs your children know and love.</p>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">🎮</div>
                <h3>Party Games</h3>
                <p>Age-appropriate group activities and games designed to keep children engaged and entertained throughout the event.</p>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">🎂</div>
                <h3>Birthday Parties</h3>
                <p>Complete birthday party packages tailored to your child's favorite characters and interests, creating unforgettable memories.</p>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">🏫</div>
                <h3>School Events</h3>
                <p>Educational entertainment perfect for nurseries, schools, and community events with age-appropriate content.</p>
            </div>
            <div class="service-card fade-in">
                <div class="service-icon">📸</div>
                <h3>Photo Moments</h3>
                <p>Professional photo opportunities with your favorite Disney characters to capture and preserve those magical memories.</p>
            </div>
        </div>
    </div>
</section>

<section id="about" class="about section">
    <div class="container">
        <div class="about-content">
            <div class="about-text fade-in">
                <h2>About Magical Moments</h2>
                <p>Welcome to a world where Disney dreams come true! I'm a professional children's entertainer based in Sutton Coldfield, dedicated to bringing authentic Disney magic to Birmingham and the surrounding West Midlands.</p>
                <p>With years of experience in children's entertainment, I specialize in creating immersive Disney character experiences that captivate young audiences. Every performance features high-quality costumes, interactive storytelling, and age-appropriate entertainment.</p>
                <p>I believe every child deserves to meet their heroes and experience the wonder of Disney magic. Each party is carefully tailored to create those precious moments that families will treasure forever.</p>
                <p><strong>Proudly serving:</strong> Sutton Coldfield (B74), Birmingham, Tamworth, Lichfield, and throughout the West Midlands.</p>
            </div>
            <div class="about-visual fade-in">
                <span>🏰</span>
            </div>
        </div>
    </div>
</section>

<section id="testimonials" class="testimonials section">
    <div class="container">
        <div class="section-header fade-in">
            <h2 class="section-title">What Parents Say</h2>
            <p class="section-subtitle">Real reviews from families who've experienced the magic</p>
        </div>
        <div class="testimonial-grid">
            <div class="testimonial fade-in">
                <div class="stars">★★★★★</div>
                <p>"Absolutely incredible! The princess performance was so authentic and engaging. Our daughter was completely mesmerized and it made her birthday truly special. Highly recommend!"</p>
                <strong>Sarah M., Sutton Coldfield</strong>
            </div>
            <div class="testimonial fade-in">
                <div class="stars">★★★★★</div>
                <p>"Professional, punctual, and absolutely wonderful with the children. The interactive games and singing kept all the kids entertained. Worth every penny!"</p>
                <strong>Mark & Lisa T., Birmingham</strong>
            </div>
            <div class="testimonial fade-in">
                <div class="stars">★★★★★</div>
                <p>"Our son still talks about meeting his favorite Disney character months later. The attention to detail and genuine care for the children really shows. Amazing service!"</p>
                <strong>Emma R., Tamworth</strong>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="contact section">
    <div class="container">
        <div class="section-header fade-in">
            <h2 class="section-title">Book Your Magical Moment</h2>
            <p class="section-subtitle">Ready to create unforgettable memories? Get in touch today</p>
        </div>
        <div class="contact-grid">
            <div class="contact-card fade-in">
                <div class="contact-icon">📱</div>
                <h3>Phone</h3>
                <p>07XXX XXX XXX</p>
                <p>Available 9AM - 8PM daily</p>
            </div>
            <div class="contact-card fade-in">
                <div class="contact-icon">✉️</div>
                <h3>Email</h3>
                <p>hello@magicalmoments.co.uk</p>
                <p>24-hour response time</p>
            </div>
            <div class="contact-card fade-in">
                <div class="contact-icon">📍</div>
                <h3>Service Area</h3>
                <p>Sutton Coldfield (B74)</p>
                <p>Birmingham & West Midlands</p>
            </div>
            <div class="contact-card fade-in">
                <div class="contact-icon">💰</div>
                <h3>Pricing</h3>
                <p>From £80 per party</p>
                <p>Free consultations available</p>
            </div>
        </div>
        <div class="contact-cta fade-in">
            <a href="tel:07XXXXXXXXX" class="cta-button">Call Now for Free Quote</a>
        </div>
    </div>
</section>

<script>
    // Smooth scrolling
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            const target = document.querySelector(this.getAttribute('href'));
            if (target) {
                target.scrollIntoView({
                    behavior: 'smooth',
                    block: 'start'
                });
            }
        });
    });

    // Navbar scroll effect
    window.addEventListener('scroll', () => {
        const navbar = document.querySelector('.navbar');
        if (window.scrollY > 100) {
            navbar.style.background = 'rgba(255, 255, 255, 0.98)';
            navbar.style.boxShadow = '0 10px 30px rgba(0,0,0,0.1)';
        } else {
            navbar.style.background = 'rgba(255, 255, 255, 0.95)';
            navbar.style.boxShadow = 'none';
        }
    });

    // Fade in animation on scroll
    const observerOptions = {
        threshold: 0.1,
        rootMargin: '0px 0px -100px 0px'
    };

    const observer = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add('visible');
            }
        });
    }, observerOptions);

    document.querySelectorAll('.fade-in').forEach(el => {
        observer.observe(el);
    });

    // Add some micro-interactions
    document.querySelectorAll('.service-card, .testimonial, .contact-card').forEach(card => {
        card.addEventListener('mouseenter', function() {
            this.style.transform = 'translateY(-5px) scale(1.02)';
        });
        
        card.addEventListener('mouseleave', function() {
            this.style.transform = 'translateY(0) scale(1)';
        });
    });
</script>
```

</body>
</html>
