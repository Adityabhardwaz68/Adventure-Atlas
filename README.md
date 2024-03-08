# Adventure-Atlas
created a solution/idea that can boost the current situation of the tourism industries including hotels, travel and others.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tourism Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Tourism Website</h1>
        <p>Explore the world with us!</p>
    </header>
    <main>
        <section id="destination">
            <h2>Popular Destinations</h2>
            <div class="destination-gallery">
                <!-- Images and videos go here -->
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Tourism Website. All rights reserved.</p>
    </footer>
</body>
</html>
<!-- Inside the <main> tag -->
<section id="search">
    <h2>Find Your Next Adventure</h2>
    <form action="search.php" method="GET">
        <label for="destination">Destination:</label>
        <input type="text" id="destination" name="destination" required>
        <label for="dates">Travel Dates:</label>
        <input type="date" id="dates" name="dates" required>
        <label for="preferences">Preferences:</label>
        <textarea id="preferences" name="preferences" placeholder="Any specific preferences"></textarea>
        <button type="submit">Search</button>
    </form>
</section>
<!-- Inside the <main> tag -->
<section id="guides">
    <h2>Destination Guides</h2>
    <!-- Destination guides content goes here -->
</section>
<!-- Inside the <main> tag -->
<section id="offers">
    <h2>Special Offers</h2>
    <!-- Special offers content goes here -->
</section>
<!-- Inside the <header> tag -->
<nav>
    <ul>
        <li><a href="login.php">Login</a></li>
        <li><a href="register.php">Register</a></li>
    </ul>
</nav>
