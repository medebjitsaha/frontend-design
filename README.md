<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Maverick Education - A platform to be trained as Maverick">
    <meta name="keywords" content="Maverick, Education, Training">
    <title>Maverick Education</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
        }

        /* Header Styles */
        header {
            background-color:rgba(39, 23, 104, 0.764);
            color: rgb(8, 8, 8);
            text-align: center;
            padding: 2rem;
        }

        .logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .logo {
            max-width: 80px;
            height: auto;
        }

        .header-text {
            text-align: middle;
        }

        /* Navigation Styles */
        nav {
            background-color: #080808;
            padding: 1rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        nav a:hover {
            color: #ff9900;
        }

        /* Main Content Styles */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
            display: flex;
            gap: 2rem;
        }

        main {
            flex: 3;
        }

        aside {
            flex: 1;
            background-color: #f4f4f4;
            padding: 1rem;
        }

        /* Article Styles */
        article {
            margin-bottom: 2rem;
            padding: 1rem;
            border-bottom: 1px solid #ddd;
        }

        /* Footer Styles */
        footer {
            background-color: #030303;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo-container">
            <img src="logo.png" alt="Maverick Education Logo" class="logo">
            <div class="header-text">
                <h1>MAVERICK EDUCATION CAMP</h1>
                <p><u>[A platform to train and become Maverick,"Marksman & Leaders"]</u></p>
            </div>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        <main>
            <article>
                <h2>Welcome to Our CAMP</h2>
                <p>A warm greetings to our viewers, and warm welcome.</p>
            </article>

            <article>
                <h2>Latest News</h2>
                <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
            </article>
        </main>

        <aside>
            <h3>Sidebar</h3>
            <ul>
                <li>Latest Updates</li>
                <li>Archives</li>
                <li>Social Media</li>
            </ul>
        </aside>
    </div>

    <footer>
        <p>&copy; 2025 Maverick Education Camp. All rights reserved.</p>
    </footer>
</body>
</html>
