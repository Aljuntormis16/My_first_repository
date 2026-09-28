<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Projects</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav>
            <h2>My Information Design</h2>
            <a href="#projects">Projects</a>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h1>My Projects</h1>
            <p>Here are some of my Information Technology projects and designs.</p>
        </section>

        <section id="projects" class="projects">

            <div class="project-card">
                <div class="icon">🏍️</div>
                <h2>MotorPartsTrack</h2>
                <p>
                    A web-based inventory management system developed
                    for J&J Motor Parts and Accessories Shop.
                </p>
                <ul>
                    <li>Inventory Management</li>
                    <li>Stock Monitoring</li>
                    <li>Low Stock Alerts</li>
                    <li>Inventory Reports</li>
                </ul>
                <button onclick="showProject('motorparts')">
                    View Project
                </button>
            </div>

            <div class="project-card">
                <div class="icon">🏍️</div>
                <h2>Aljun Moto</h2>
                <p>
                    A motorcycle buy, sell, and trade information
                    and promotional website concept.
                </p>
                <ul>
                    <li>Motorcycle Listings</li>
                    <li>Buy and Sell</li>
                    <li>Trade Information</li>
                    <li>Motorcycle Promotions</li>
                </ul>
                <button onclick="showProject('aljun')">
                    View Project
                </button>
            </div>

            <div class="project-card">
                <div class="icon">🍽️</div>
                <h2>Online Restaurant Reservation</h2>
                <p>
                    A prototype system designed to help customers
                    view restaurant information and make reservations.
                </p>
                <ul>
                    <li>Restaurant Information</li>
                    <li>Reservation Form</li>
                    <li>Customer Details</li>
                    <li>Reservation Management</li>
                </ul>
                <button onclick="showProject('restaurant')">
                    View Project
                </button>
            </div>

        </section>
    </main>

    <footer>
        <p>© 2026 My Information Design | GitHub Project</p>
    </footer>

    <script src="script.js"></script>
</body>
</html># My_first_repository