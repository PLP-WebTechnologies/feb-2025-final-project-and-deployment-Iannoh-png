<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog Website</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
    <style>
      /* --- General Styles --- */
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        color: #333;
        line-height: 1.7;
      }
      .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
      }
      /* --- Layout Styles --- */
      header {
        background-color: #2c3e50;
        color: white;
        padding: 20px 0;
        text-align: center;
      }
      header h1{
        margin: 0;
      }
      nav {
        background-color: #34495e;
        color: white;
        padding: 10px 0;
      }
      nav ul {
        list-style: none;
        display: flex;
        justify-content: center;
        margin: 0;
        padding: 0;
      }
      nav ul li {
        margin: 0 15px;
      }
      nav ul li a {
        color: white;
        text-decoration: none;
        font-weight: bold;
        font-size: 1.1em;
      }
      nav ul li a:hover {
        color: #f1c40f;
      }
      main {
        padding: 20px;
        min-height: 400px;
      }
      footer {
        background-color: #2c3e50;
        color: white;
        padding: 20px 0;
        text-align: center;
        margin-top: 20px;
      }
      /* --- Page Styles --- */
      .home-section {
        text-align: center;
      }
      .blog-section {
        display: flex;
        flex-direction: column;
        align-items: center;
      }
      .blog-post {
        margin-bottom: 20px;
        padding: 20px;
        background-color: #fff;
        border: 1px solid #ddd;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        width: 80%;
      }
      .blog-post h2 {
        margin-bottom: 10px;
        color: #3498db;
      }
      .blog-post p{
        color:#555;
      }
       .blog-post img{
        max-width: 100%;
        height: auto;
        margin-bottom: 10px;
       }
      .tab-content{
        display: none;
      }
      .tab-content.active{
        display: block;
      }
      .tab-button{
        padding: 10px 20px;
        border: none;
        background-color: #ddd;
        margin-right: 10px;
        cursor: pointer;
        border-radius: 5px;
      }
      .tab-button.active{
        background-color: #3498db;
        color: #fff;
      }
      #gallery-container{
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 10px;
      }
      #gallery-container img{
        max-width: 80%;
        height: auto;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.2);
      }
      /* --- Responsive Styles --- */
      @media (max-width: 768px) {
        nav ul {
          flex-direction: column;
          text-align: center;
        }
        nav ul li {
          margin: 10px 0;
        }
        .main-content {
            flex-direction: column;
            align-items: center;
        }
        .section{
          width: 90%;
        }
        .blog-post{
            width: 95%;
        }
      }
    </style>
</head>
<body>
    <header>
        <h1>My Blog</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#about">About</a></li>
             <li><a href="#gallery">Gallery</a></li>
              <li><a href="#form">Form</a></li>
        </ul>
    </nav>
    <main class="container">
        <section id="home" class="home-section">
            <h2>Welcome to My Blog</h2>
            <p>This is a place where I share my thoughts and ideas.</p>
        </section>
        <section id="blog" class="blog-section">
            <div class="blog-post">
                <h2>First Post: My Trip to the Mountains</h2>
                <p>I recently visited the mountains, and it was an incredible experience.  The views were breathtaking, and the air was so fresh. I went hiking and saw some amazing wildlife.  I took this photo of a beautiful lake.</p>
                <img src="https://placehold.co/600x400/EEE/31343C" alt="Mountain Lake">
                <p>I can't wait to go back again!</p>
            </div>
            <div class="blog-post">
                <h2>Second Post: Best Coffee Shops in Town</h2>
                <p>I've been exploring the coffee scene in our town, and I've found some amazing places.  Here are a few of my favorites:</p>
                 <ol>
                    <li>The Daily Grind: Great coffee and pastries.</li>
                    <li>Coffee Paradise: Cozy atmosphere and friendly staff.</li>
                    <li>Bean Me Up: Best lattes in town!</li>
                 </ol>
            </div>
        </section>
        <section id="about" class="home-section">
            <h2>About Me</h2>
            <p>I am a passionate blogger who loves to share my experiences and connect with readers. I believe in the power of storytelling to inspire and inform.</p>
        </section>
        <section id="gallery" class="home-section">
            <h2>Image Gallery</h2>
            <div id="gallery-container">
                <img src="https://placehold.co/400x300/EEE/8E44AD" alt="Purple Flowers">
                <img src="https://placehold.co/400x300/EEE/27AE60" alt="Green Forest">
                <img src="https://placehold.co/400x300/EEE/F39C12" alt="Orange Sunset">
            </div>
        </section>
        <section id="form" class="home-section">
            <h2>Registration Form</h2>
            <form id="registration-form" action="#" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>

                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter your password" required>

                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" placeholder="Enter your date of birth">

                <label for="gender">Gender:</label>
                <select id="gender" name="gender">
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select>

                <div class="radio-group">
                    <label>
                        <input type="radio" name="program" value="btech"> B.Tech
                    </label>
                    <label>
                        <input type="radio" name="program" value="mtech"> M.Tech
                    </label>
                    <label>
                        <input type="radio" name="program" value="phd"> PhD
                    </label>
                </div>

                <div class="checkbox-group">
                    <label>
                        <input type="checkbox" id="newsletter" name="newsletter" value="yes"> Subscribe to newsletter
                    </label>
                    <label>
                        <input type="checkbox"  name="terms" value="yes" required> I agree to terms and conditions
                    </label>
                </div>

                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" cols="50" placeholder="Enter your message here..."></textarea>

                <button type="submit">Register</button>
                <button type="reset">Clear Form</button>
            </form>
            <button id="local-storage-button" class = "animated-button">Save Preferences</button>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>
</body>
</html>

