<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" href="styles.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Art for Sale</title>
    <style>
        body {
            font-family: cursive, Sans-Serif;
            margin: 0;
            padding: 0;
            background-color: #4fb398;
        }
        header {
            background-color: #216e59;
            color: white;
            padding: 15px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 5px;
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        .gallery .art-item {
            text-align: center;
        }
        .art-item a {
            display: block;
            text-decoration: none;
            color: black;
        }
        .art-item button {
            background-color: #007BFF;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .art-item button:hover {
            background-color: #0056b3;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: white;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }
        .contact-form label {
            display: block;
            margin-bottom: 5px;
            font-weight: medium;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        .contact-form button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .contact-form button:hover {
            background-color: #216e59;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Saman's Art Gallery</h1>
        <p>Discover and purchase unique artwork</p>
    </header>
    
    <nav>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container" id="gallery">
        <h2>Art Gallery</h2>
        <div class="gallery">
            <div class="art-item">
                <a href="artwork1.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/4a687a8b-a4ec-498c-b1fa-c1715823d9a2.JPG" alt="Artwork 1">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork2.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/77e11740-9af2-493b-b897-6f60b5b7ef9f.JPG" alt="Artwork 2">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork3.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/99733939-c467-4107-98c8-6fef42def926.JPG" alt="Artwork 3">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork4.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2024-12-31-14-33-21.jpg" alt="Artwork 4">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork5.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2024-12-31-14-33-23%202.jpg" alt="Artwork 5">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork6.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2024-12-31-14-33-23.jpg" alt="Artwork 6">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork7.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2024-12-31-14-33-22.jpg" alt="Artwork 7">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork8.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2025-01-01-10-52-05.jpg" alt="Artwork 8">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork9.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2025-01-01-10-53-00.jpg" alt="Artwork 9">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork10.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2025-01-01-10-54-03.jpg" alt="Artwork 10">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork11.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2025-01-01-10-54-40.jpg" alt="Artwork 11">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork12.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2025-01-01-10-55-06.jpg" alt="Artwork 12">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
            <div class="art-item">
                <a href="artwork13.html">
                    <img src="https://assets.onecompiler.app/434huapx2/434hu9rk5/PHOTO-2025-01-01-10-55-38.jpg" alt="Artwork 13">
                    <p>Title: </p>
                    <p>Price: $</p>
                </a>
            </div>
           
                </a>
            </div>
        </div>
    </div>

    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <h4>Follow @samanartgallery on Instagram and Facebook or Call 012345678.</h4> 
        
        <form class="contact-form" action="contact.php" method="POST">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </div>

    <footer>
        <p>&copy; 2024 Saman's Art Store. All rights reserved.</p>
    </footer>
</body>
</html>


