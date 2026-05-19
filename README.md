<html lang="en"><head>
    <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>WKD Esports</title>
            <style>
                * {
                    margin: 0;
                padding: 0;
                box-sizing: border-box;
                font-family: Arial, Helvetica, sans-serif;
    }

                body {
                    background: #0b0b0f;
                color: white;
                line-height: 1.6;
    }

                header {
                    background: linear-gradient(90deg, #6a00ff, #00d4ff);
                padding: 20px 50px;
                display: flex;
                justify-content: space-between;
                align-items: center;
                position: sticky;
                top: 0;
                z-index: 1000;
    }

                header h1 {
                    font - size: 2rem;
                font-weight: bold;
    }

                nav a {
                    color: white;
                text-decoration: none;
                margin-left: 20px;
                transition: 0.3s;
                font-weight: bold;
    }

                nav a:hover {
                    color: #000;
    }

                .hero {
                    height: 90vh;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                text-align: center;
                background: url('https://images.unsplash.com/photo-1542751371-adc38448a05e?q=80&w=2070&auto=format&fit=crop') center/cover no-repeat;
                position: relative;
    }

                .hero::before {
                    content: "";
                position: absolute;
                top: 0;
                left: 0;
                width: 100%;
                height: 100%;
                background: rgba(0,0,0,0.7);
    }

                .hero-content {
                    position: relative;
                z-index: 1;
                padding: 20px;
    }

                .hero h2 {
                    font - size: 4rem;
                margin-bottom: 20px;
                text-shadow: 0 0 15px #00d4ff;
    }

                .hero p {
                    font - size: 1.3rem;
                margin-bottom: 30px;
    }

                .btn {
                    display: inline-block;
                padding: 14px 35px;
                background: #00d4ff;
                color: black;
                font-weight: bold;
                text-decoration: none;
                border-radius: 30px;
                transition: 0.3s;
    }

                .btn:hover {
                    background: white;
                transform: scale(1.05);
    }

                section {
                    padding: 80px 50px;
    }

                .section-title {
                    text - align: center;
                margin-bottom: 50px;
                font-size: 2.5rem;
                color: #00d4ff;
    }

                .cards {
                    display: grid;
                grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
                gap: 25px;
    }

                .card {
                    background: #15151d;
                padding: 25px;
                border-radius: 15px;
                transition: 0.3s;
                border: 1px solid #222;
    }

                .card:hover {
                    transform: translateY(-10px);
                border-color: #00d4ff;
                box-shadow: 0 0 15px rgba(0, 212, 255, 0.5);
    }

                .card h3 {
                    margin - bottom: 15px;
                color: #00d4ff;
    }

                .team-member {
                    text - align: center;
    }

                .team-member img {
                    width: 120px;
                height: 120px;
                border-radius: 50%;
                margin-bottom: 15px;
                border: 3px solid #00d4ff;
    }

                .contact {
                    text - align: center;
    }

                .contact p {
                    margin - bottom: 15px;
    }

                footer {
                    background: #111;
                text-align: center;
                padding: 25px;
                border-top: 2px solid #00d4ff;
    }

                @media (max-width: 768px) {
                    header {
                    flex - direction: column;
                gap: 15px;
      }

                .hero h2 {
                    font - size: 2.5rem;
      }

                section {
                    padding: 60px 20px;
      }
    }
            </style>
</head>
        <body>

            <header>
                <h1>WKD Esports</h1>
                <nav>
                    <a href="#home">Home</a>
                    <a href="#about">About</a>
                    <a href="#team">Team</a>
                    <a href="#matches">Matches</a>
                    <a href="#contact">Contact</a>
                </nav>
            </header>

            <section class="hero" id="home">
                <div class="hero-content">
                    <h2>WELCOME TO WKD ESPORTS</h2>
                    <p>Competitive Gaming - Streaming - Content Creation</p>
                    <a href="#team" class="btn">Meet The Team</a>
                </div>
            </section>

            <section id="about">
                <h2 class="section-title">About Us</h2>
                <div class="cards">
                    <div class="card">
                        <h3>Who We Are</h3>
                        <p>
                            WKD Esports is a competitive gaming organization focused on dominating tournaments,
                            creating entertaining content, and building a strong gaming community.
                        </p>
                    </div>

                    <div class="card">
                        <h3>Our Mission</h3>
                        <p>
                            We aim to inspire gamers around the world through teamwork, skill, and dedication.
                        </p>
                    </div>

                    <div class="card">
                        <h3>Games We Play</h3>
                        <p>
                            Valorant, Fortnite, Call of Duty, Apex Legends, Rocket League, and more.
                        </p>
                    </div>
                </div>
            </section>

            <section id="team">
                <h2 class="section-title">Our Team</h2>

                <div class="cards">
                    <div class="card team-member">
                        <img src="file:///C:/Users/shaun/Downloads/content.png" alt="Player 1">
                            <h3>CIA</h3>
                            <p>Team Captain</p>
      </div>

                        <div class="card team-member">
                            <img src="file:///C:/Users/shaun/Downloads/file_0000000026f8722f95f969c0865c555f.png" alt="Player 2">
                                <h3>FaZe Nate</h3>
                                <p>Sniper Specialist</p>
      </div>

                            <div class="card team-member">
                                <img src="file:///C:/Users/shaun/Downloads/content1.png" alt="Player 3">
                                    <h3>DarkNova</h3>
                                    <p>Content Creator</p>
      </div>
                            </div>
  </section>

                        <section id="matches">
                            <h2 class="section-title">Upcoming Matches</h2>

                            <div class="cards">
                                <div class="card">
                                    <h3>WKD vs Alpha Squad</h3>
                                    <p>Date: June 5, 2026</p>
                                    <p>Game: Valorant</p>
                                </div>

                                <div class="card">
                                    <h3>WKD vs Titan Force</h3>
                                    <p>Date: June 12, 2026</p>
                                    <p>Game: Fortnite</p>
                                </div>

                                <div class="card">
                                    <h3>WKD vs Night Hunters</h3>
                                    <p>Date: June 20, 2026</p>
                                    <p>Game: Apex Legends</p>
                                </div>
                            </div>
                        </section>

                        <section id="contact" class="contact">
                            <h2 class="section-title">Contact Us</h2>
                            <p>Email: contact@wkdesports.com</p>
                            <p>Twitter/X: @WKDEsports</p>
                            <p>Twitch: twitch.tv/wkdesports</p>
                            <a href="#home" class="btn">Back To Top</a>
                        </section>

                        <footer>
                            <p>© 2026 WKD Esports. All Rights Reserved.</p>
                        </footer>



</body></html>
