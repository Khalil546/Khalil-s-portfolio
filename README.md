# Khalil-s-portfolio
A mini model portfolio to help for brand visibility
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Model Portfolio | Your Name</title>
    <style>
        :root {
            --bg-color: #fdfdfd;
            --text-color: #1a1a1a;
            --accent-color: #7a7a7a;
        }

        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        /* Navigation */
        nav {
            padding: 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            background: rgba(253, 253, 253, 0.9);
            z-index: 1000;
        }

        .logo { font-weight: bold; letter-spacing: 2px; text-transform: uppercase; }

        /* Hero Section */
        .hero {
            height: 80vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: #f4f4f4; /* Placeholder for a large high-fashion image */
        }

        /* Gallery Grid */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 15px;
            padding: 2rem;
        }

        .gallery img {
            width: 100%;
            height: auto;
            filter: grayscale(20%);
            transition: 0.3s ease;
        }

        .gallery img:hover { filter: grayscale(0%); }

        /* Stats Section */
        .stats {
            padding: 4rem 2rem;
            background: #fff;
            text-align: center;
            border-top: 1px solid #eee;
        }

        .stats-grid {
            display: flex;
            justify-content: center;
            gap: 3rem;
            flex-wrap: wrap;
            text-transform: uppercase;
            font-size: 0.9rem;
            letter-spacing: 1px;
        }

        /* Contact */
        .contact { padding: 4rem 2rem; text-align: center; }
        .btn {
            padding: 12px 30px;
            border: 1px solid #000;
            text-decoration: none;
            color: #000;
            transition: 0.3s;
        }
        .btn:hover { background: #000; color: #fff; }

        @media (max-width: 600px) {
            .stats-grid { gap: 1rem; flex-direction: column; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">YOUR NAME</div>
        <div class="links">Editorial • Commercial • Contact</div>
    </nav>

    <section class="hero">
        <h1>PORTFOLIO 2026</h1>
    </section>

    <div class="gallery">
        <img src="your-best-editorial.jpg" alt="Editorial Work">
        <img src="your-commercial-work.jpg" alt="Commercial Concept">
        <img src="natural-polaroid.jpg" alt="Digital Polaroid">
        <img src="cinematic-concept.jpg" alt="VBL Visuals">
    </div>

    <section class="stats">
        <h2>STATISTICS</h2>
        <div class="stats-grid">
            <div><strong>Height:</strong> 5'10"</div>
            <div><strong>Bust:</strong> 32</div>
            <div><strong>Waist:</strong> 24</div>
            <div><strong>Hips:</strong> 34</div>
            <div><strong>Location:</strong> Lagos / Worldwide</div>
        </div>
    </section>

    <section class="contact">
        <h2>WORK WITH ME</h2>
        <p>Available for editorial, commercial, and brand collaborations.</p>
        <br>
        <a href="mailto:your@email.com" class="btn">SEND INQUIRY</a>
    </section>

</body>
</html>
