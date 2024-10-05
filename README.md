# cusine-website
cusine website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <link rel="stylesheet" href="recipe.css">
</head>
<body>
    
    <nav>
        <header class="d-flex justify-content-center py-3">
            <ul class="nav nav-pills">
                <li><img class="img1" src="Flavors Unleashed (1).jpg" alt="" height="80px" width="100px"></li>
                <li class="nav-item"><a href="#" class="nav-link active" aria-current="page">Home</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Features</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Pricing</a></li>
                <li class="nav-item"><a href="#" class="nav-link">FAQs</a></li>
                <li class="nav-item"><a href="#" class="nav-link">About</a></li>
            </ul>
        </header>
    </nav>
    
    <div class="hero-section">
        <div class="carousel">
            <div class="carousel-item active">
                <img src="platter3.jpg" alt="Sushi">
            </div>
            <div class="carousel-item">
                <img src="tacos.jpg" alt="Tacos">
            </div>
            <div class="carousel-item">
                <img src="pasta.jpg" alt="Pasta">
            </div>
            <div class="carousel-item">
                <img src="curry.jpg" alt="Curry">
            </div>
        </div>
        <div class="hero-text">
            <h1>Flavors Unleashed: A Culinary Adventure Awaits!</h1>
            <p>Let Your Creativity Cook Something Delicious!</p>
            <a href="#recipes" class="cta-button">Start Your Flavor Journey</a>
        </div>
    </div>

    <div class="d-flex gap-2 justify-content-center py-5">
        <button class="btn btn-secondary rounded-pill px-3" type="button">Your Choice</button>
        <button class="btn btn-success rounded-pill px-3" type="button">Veg</button>
        <button class="btn btn-danger rounded-pill px-3" type="button">Non-Veg</button>
    </div>
    
    <div class="row mb-2">
        <div class="col-md-6">
            <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col p-4 d-flex flex-column position-static">
                    <strong class="d-inline-block mb-2 text-primary-emphasis">World</strong>
                    <h3 class="mb-0">Taste of Sunrise</h3>
                    <div class="mb-1 text-body-secondary">Nov 12</div>
                    <p class="card-text mb-auto">Enjoy a local beachside brunch to start the day gently with the flavors of Saint-Martin.</p>
                    <a href="#" class="icon-link gap-1 icon-link-hover stretched-link">Continue reading</a>
                </div>
                <div class="col-auto d-none d-lg-block">
                    <img src="curry.jpg" alt="dkb" height="250px" width="200px">
                </div>
            </div>
        </div>
        <div class="col-md-6">
            <div class="row g-0 border rounded overflow-hidden flex-md-row mb-4 shadow-sm h-md-250 position-relative">
                <div class="col p-4 d-flex flex-column position-static">
                    <strong class="d-inline-block mb-2 text-success-emphasis">Design</strong>
                    <h3 class="mb-0">Post title</h3>
                    <div class="mb-1 text-body-secondary">Nov 11</div>
                    <p class="mb-auto">This is a wider card with Enjoy a local beachside brunch to start the day gently with the flavors of Saint-Martino additional content.</p>
                    <a href="#" class="icon-link gap-1 icon-link-hover stretched-link">Continue reading</a>
                </div>
                <div class="col-auto d-none d-lg-block">
                    <img src="tacos.jpg" alt="dkb" height="250px" width="200px">
                </div>
            </div>
        </div>
    </div>

    <!-- New Article Section -->
    <section class="articles-section py-5">
        <h2 class="text-center mb-4">Culinary Showdowns</h2>
        <div class="row">
            <div class="col-md-6">
                <article class="card mb-4 shadow-sm">
                    <div class="card-body">
                        <h2 class="card-title">The Great Pasta Debate: Spaghetti vs. Fettuccine</h2>
                        <p class="card-text">Welcome, food warriors! Today, we dive into a culinary battlefield where spaghetti and fettuccine fight for the title of "Ultimate Pasta Champion!" 🍝💥</p>
                        <a href="#" class="btn btn-primary">Read More</a>
                    </div>
                </article>
            </div>
            <div class="col-md-6">
                <article class="card mb-4 shadow-sm">
                    <div class="card-body">
                        <h2 class="card-title">Dessert Wars: Cake vs. Ice Cream 🍰🍦</h2>
                        <p class="card-text">Welcome back to the sweetest showdown! Today, we pit cake against ice cream in a dessert duel for the ages! Who will come out on top? 🎉</p>
                        <a href="#" class="btn btn-primary">Read More</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <div class="container">
        <div class="image-container">
            <img src="pasta.jpg" height="1000px" alt="Village" class="blinking-image">
            
        </div>
        <div class="text-container">
            <h2>Barbecue competition</h2>
            <p>The barbecue competition will be a highlight of the Saint-Martin Gastronomy Festival, this event is open to all.</p>
            <button class="action-button">Register</button>
        </div>
    </div>

    <div class="container">
        <div class="text-container">
            <h2>Cooking workshops</h2>
            <p>Young and old will participate in outdoor cooking workshops led by local and international chefs, discovering new techniques, exploring new flavors, and most importantly, having fun!</p>
            <button class="action-button">Cooking Workshops</button>
        </div>
        <div class="image-container">
            <img src="women.avif" alt="Village" class="blinking-image">
            
            
        </div>
    </div>
    
    
    <div class="row">
        <div class="col-12 col-md">
            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="d-block mb-2" role="img" viewBox="0 0 24 24">
                <title>Product</title>
                <circle cx="12" cy="12" r="10"></circle>
                <path d="M14.31 8l5.74 9.94M9.69 8h11.48M7.38 12l5.74-9.94M9.69 16L3.95 6.06M14.31 16H2.83m13.79-4l-5.74 9.94"></path>
            </svg>
            <small class="d-block mb-3 text-body-secondary">© 2017–2024</small>
        </div>
        <div class="col-6 col-md">
            <h5>Features</h5>
            <ul class="list-unstyled text-small">
                <li><a class="link-secondary text-decoration-none" href="#">Cool stuff</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Random feature</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Team feature</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Stuff for developers</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Another one</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Last time</a></li>
            </ul>
        </div>
        <div class="col-6 col-md">
            <h5>Resources</h5>
            <ul class="list-unstyled text-small">
                <li><a class="link-secondary text-decoration-none" href="#">Resource name</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Resource</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Another resource</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Final resource</a></li>
            </ul>
        </div>
        <div class="col-6 col-md">
            <h5>Categories</h5>
            <ul class="list-unstyled text-small">
                <li><a class="link-secondary text-decoration-none" href="#">Business</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Education</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Government</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Gaming</a></li>
            </ul>
        </div>
        <div class="col-6 col-md">
            <h5>About</h5>
            <ul class="list-unstyled text-small">
                <li><a class="link-secondary text-decoration-none" href="#">Team</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Locations</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Privacy</a></li>
                <li><a class="link-secondary text-decoration-none" href="#">Terms</a></li>
            </ul>
        </div>
    </div>
    

    <script src="script.js"></script>
</body>
</html>











* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: #edf2f7;
    font-family: Arial, sans-serif;
}

.nav-link {
    color: black;
}

nav {
    background-color: #e7cf8d; /* Changed to match footer */
    color: rgb(249, 250, 251);
    font-family: "Playfair Display", serif;
    font-weight: bolder;
    position: sticky;
    top: 0; /* Stick to the top of the viewport */
    z-index: 1000; /* Ensure it stays above other content */

}

.nav-link.active {
    background-color: orange;
    color: white;
}

.nav-link:hover {
    background-color: rgba(255, 165, 0, 0.7);
    color: white;
}

.img1 {
    margin-right: 500px;
}

h1 {
    color: #f4f4f0;
    font-style: italic;
    font-weight: bold;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.hero-section {
    position: relative;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    min-height: 400px;
    overflow: hidden;
}

.carousel {
    width: 100%;
    overflow: hidden;
}

.carousel-item {
    position: relative;
    width: 100%;
}

.carousel-item img {
    width: 100%;
    height: 500px;
    object-fit: cover;
    transition: transform 0.5s ease;
}

.carousel-item img:hover {
    transform: scale(1.1);
}

.hero-text {
    position: absolute;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    color: white;
    padding: 10px;
}

.cta-button {
    background-color: #ff5733;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.cta-button:hover {
    background-color: #e84a29;
}

.articles-section {
    background-color: #ffffff;
    padding: 20px;
    border-radius: 10px;
}

.card {
    border: none;
    transition: transform 0.2s ease;
}

.btn-primary {
    background-color: orange;
    color: white;
    border: none;
}

.btn-primary:hover {
    background-color: darkorange;
    color: white;
}

.card-title {
    color: rgb(191, 19, 159);
}

.card:hover {
    transform: translateY(-5px);
}

.blog-post {
    cursor: pointer;
}

.link-body-emphasis:hover {
    color: #ff6347;
    transform: scale(1.05);
    transition: transform 0.2s ease, color 0.2s ease;
}

.recipe-card {
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.recipe-card:hover {
    transform: scale(1.05);
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
}

.dmRespRow {
    display: flex;
    justify-content: space-between;
}

.dmRespCol {
    flex: 1;
    padding: 0 10px;
}

.imageWidget img {
    width: 100%;
    height: auto;
    max-width: 150px;
    margin: 0 auto;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    margin: 0;
    padding: 20px;
}

.container {
    display: flex;
    align-items: center;
    background-color: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.image-container {
    flex: 1;
    display: flex;
    justify-content: center;
    padding-right: 20px;
}

.blinking-image {
    width: 550px;
    height: 200px;
    animation: blink-animation 4s steps(5, start) infinite;
}

@keyframes blink-animation {
    from {
        opacity: 1;
    }
    to {
        opacity: 0.8;
    }
}

h2 {
    color: #941d4e;
}

p {
    color: #ca7104;
}

.action-button {
    background-color: orange;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s; 
}

.action-button:hover {
    background-color: darkorange;
}

.row {
    background-color: #e7cf8d;
    padding: 20px;
    color: #333;
}

h5 {
    color: #ff5733;
    font-family: 'Comic Sans MS', cursive, sans-serif;
    text-transform: uppercase;
    margin-bottom: 15px;
}

.list-unstyled li {
    margin-bottom: 10px;
}

.link-secondary {
    color: #ffffff;
    text-decoration: none;
    transition: color 0.3s ease;
}

.link-secondary:hover {
    color: #ff5733;
    text-decoration: underline;
}

.text-body-secondary {
    color: #555;
}
