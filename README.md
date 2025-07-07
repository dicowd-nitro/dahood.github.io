<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Da Hood Official Site - Streets & Stories</title>
    <link href="https://fonts.googleapis.com/css2?family=Aldrich&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header id="main-header">
        <div class="container header-content">
            <h1>Da Hood Fan Zone</h1>
            <nav>
                <ul>
                    <li><a href="#about" class="nav-link">About Da Hood</a></li>
                    <li><a href="#features" class="nav-link">Key Features</a></li>
                    <li><a href="#community" class="nav-link">Community</a></li>
                    <li><a href="#tips" class="nav-link">Tips & Tricks</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="about" class="hero-section" data-animation="fade-in-up">
            <div class="container">
                <h2 data-animation="fade-in-up" data-delay="100">Explore the Streets of Da Hood</h2>
                <p data-animation="fade-in-up" data-delay="200">Dive into the intense world of Roblox's Da Hood, where you can choose your path as a criminal or a law enforcer. Experience thrilling shootouts, strategic robberies, and dynamic role-playing.</p>
                <button id="learnMoreBtn" class="btn primary-btn" data-animation="fade-in-up" data-delay="300">Learn More About the Game</button>
            </div>
        </section>

        <section id="features" class="info-section" data-animation="fade-in">
            <div class="container">
                <h2 data-animation="fade-in-up">Key Features</h2>
                <div class="feature-grid">
                    <div class="feature-item" data-animation="fade-in-left">
                        <h3>Criminal Life</h3>
                        <p>Rob banks, engage in turf wars, and build your reputation on the dangerous streets.</p>
                    </div>
                    <div class="feature-item" data-animation="fade-in-up" data-delay="100">
                        <h3>Law Enforcement</h3>
                        <p>Join the police force, patrol the city, and bring criminals to swift justice.</p>
                    </div>
                    <div class="feature-item" data-animation="fade-in-up" data-delay="200">
                        <h3>Deep Customization</h3>
                        <p>Personalize your character's look, weapons, and vehicles to stand out.</p>
                    </div>
                    <div class="feature-item" data-animation="fade-in-right">
                        <h3>Active Community</h3>
                        <p>Connect with other players, form powerful crews, and compete for dominance.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="community" class="call-to-action-section" data-animation="fade-in-up">
            <div class="container">
                <h2 data-animation="fade-in-up">Join the Da Hood Community!</h2>
                <p data-animation="fade-in-up" data-delay="100">Stay updated with the latest news, events, and connect with fellow players on the official group.</p>
                <a href="https://www.roblox.com/groups/4698921/da-hood-entertainment" target="_blank" class="btn secondary-btn" data-animation="fade-in-up" data-delay="200">Visit Official Group</a>
            </div>
        </section>

        <section id="tips" class="info-section" data-animation="fade-in">
            <div class="container">
                <h2 data-animation="fade-in-up">Tips & Tricks</h2>
                <p data-animation="fade-in-up" data-delay="100">Here are some basic tips to get started and master the game. More coming soon!</p>
                <ul data-animation="fade-in-up" data-delay="200">
                    <li>Practice your aim in safe zones to improve accuracy.</li>
                    <li>Always be aware of your surroundings; danger can strike anywhere.</li>
                    <li>Team up with reliable players to increase your chances of survival.</li>
                    <li id="secretTip" class="secret-tip" style="display:none;">**Secret Tip:** Mastering the "weave" (blocking at the right time) can make you almost unhittable in combat!</li>
                </ul>
                <button id="showSecretTip" class="btn primary-btn" data-animation="fade-in-up" data-delay="300">Reveal Secret Tip</button>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Da Hood official Site.  Affiliated with Roblox And Da Hood Entertainment. All rights reserved.</p>
        </div>
    </footer>

    <button id="backToTopBtn" class="back-to-top-btn" title="Go to top">↑</button>

    <script src="script.js"></script>
</body>
</html>
