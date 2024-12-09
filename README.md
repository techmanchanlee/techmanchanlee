<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Travel</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to TechTravel.com</h1>
        <nav>
            <a href="#destinations">Destinations</a>
            <a href="#gallery">Gallery</a>
            <a href="#video">Featured Video</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <main>
        <section id="destinations">
            <h2>Top Destinations in the USA</h2>
            <article>
                <h3>Grand Canyon, Arizona</h3>
                <img src="https://images.unsplash.com/photo-1504215680853-026ed2a45def?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDF8fGdyYW5kJTIwY2FueW9ufGVufDB8fHx8MTY4NjE4MzcxNQ&ixlib=rb-4.0.3&q=80&w=1080" alt="Grand Canyon">
                <p>Marvel at the breathtaking views of one of the Seven Natural Wonders of the World.</p>
            </article>
            <article>
                <h3>Statue of Liberty, New York</h3>
                <img src="https://images.unsplash.com/photo-1529220502050-f15e570c634e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDJ8fHN0YXR1ZSUyMG9mJTIwbGliZXJ0eXxlbnwwfHx8fDE2ODYxODM3MjE&ixlib=rb-4.0.3&q=80&w=1080" alt="Statue of Liberty">
                <p>Explore the history of this iconic landmark located in New York Harbor.</p>
            </article>
            <article>
                <h3>Yellowstone National Park, Wyoming</h3>
                <img src="https://images.unsplash.com/photo-1561489287-2a017bd9365c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDJ8fHllbGxvd3N0b25lJTIwbmF0aW9uYWwlMjBwYXJrfGVufDB8fHx8MTY4NjE4MzcyOA&ixlib=rb-4.0.3&q=80&w=1080" alt="Yellowstone National Park">
                <p>Discover geysers, hot springs, and wildlife in the USA's first national park.</p>
            </article>
        </section>
        <section id="gallery">
            <h2>Travel Gallery</h2>
            <div class="gallery">
                <img src="https://images.unsplash.com/photo-1502005229762-cf1b2da7c5d6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDF8fEdvbGRlbiUyMEdhdGUlMjBCcmlkZ2V8ZW58MHx8fHwxNjg2MTgzNzM2&ixlib=rb-4.0.3&q=80&w=1080" alt="Golden Gate Bridge">
                <img src="https://images.unsplash.com/photo-1505682634904-d7c5dc70310f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDV8fExhcyUyMFZlZ2FzfGVufDB8fHx8MTY4NjE4MzczOQ&ixlib=rb-4.0.3&q=80&w=1080" alt="Las Vegas Strip">
                <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDJ8fG1pYW1pJTIwYmVhY2h8ZW58MHx8fHwxNjg2MTgzNzQx&ixlib=rb-4.0.3&q=80&w=1080" alt="Miami Beach">
                <img src="https://images.unsplash.com/photo-1571501679680-de32f1e7aad4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDF8fG1vdW50JTIwcnVzaG1vcmV8ZW58MHx8fHwxNjg2MTgzNzQ0&ixlib=rb-4.0.3&q=80&w=1080" alt="Mount Rushmore">
            </div>
        </section>
        <section id="video">
            <h2>Featured Travel Video</h2>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/h4KggqdonXU" 
                title="Travel Video" frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
            </iframe>
        </section>
        <section id="contact">
            <h2>Contact Tech Travel</h2>
            <p>Have questions or want to book a tech-savvy travel experience? Reach out to us!</p>
            <button id="contactBtn">Get in Touch</button>
            <p id="contactMessage"></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 TechTravel.com. All Rights Reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>

/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #f5f5f5;
}

/* Header */
header {
    background-image: linear-gradient(to right, #6a11cb, #2575fc);
    color: white;
    text-align: center;
    padding: 1.5rem;
}

header nav a {
    color: white;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
}

header nav a:hover {
    text-decoration: underline;
}

/* Main Content */
main {
    padding: 20px;
    text-align: center;
}

section {
    margin: 30px 0;
}

h2 {
    color: #333;
}

/* Destinations */
article {
    margin-bottom: 20px;
    text-align: left;
    background-color: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

article img {
    width: 100%;
    border-radius: 8px;
    margin-bottom: 10px;
}

/* Gallery */
.gallery {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
}

.gallery img {
    width: 300px;
    height: 200px;
    object-fit: cover;
    border-radius: 8px;
}

/* Button */
button {
    background-color: #2575fc;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
    border-radius: 5px;
    font-size: 16px;
}

button:hover {
    background-color: #1a4fb3;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}

// JavaScript for button interaction
document.getElementById('contactBtn').addEventListener('click', () => {
    const contactMessage = document.getElementById('contactMessage');
    contactMessage.textContent = 'Thank you for reaching out! We will contact you soon.';
    contactMessage.style.color = '#28a745';
});
