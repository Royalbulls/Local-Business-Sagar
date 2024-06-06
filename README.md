<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Local Business Directory</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
        }
        nav a {
            color: #fff;
            padding: 1em;
            text-decoration: none;
        }
        nav a:hover {
            background: #555;
        }
        .container {
            padding: 2em;
        }
        .search-bar {
            margin-bottom: 2em;
            text-align: center;
        }
        .search-bar input[type="text"] {
            width: 60%;
            padding: 0.5em;
            font-size: 1em;
        }
        .search-bar button {
            padding: 0.5em 1em;
            font-size: 1em;
        }
        .business-listing {
            display: flex;
            flex-wrap: wrap;
            gap: 1em;
            justify-content: space-around;
        }
        .business {
            background: #fff;
            padding: 1em;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            width: 30%;
            text-align: center;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Local Business Directory</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#categories">Categories</a>
        <a href="#add-business">Add Business</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <div class="search-bar">
            <input type="text" placeholder="Search for businesses...">
            <button>Search</button>
        </div>
        <section class="business-listing">
            <div class="business">
                <h2>Business 1</h2>
                <p>Category: Retail</p>
                <p>Location: 123 Main St.</p>
                <p>Contact: (555) 123-4567</p>
            </div>
            <div class="business">
                <h2>Business 2</h2>
                <p>Category: Food & Beverage</p>
                <p>Location: 456 Elm St.</p>
                <p>Contact: (555) 234-5678</p>
            </div>
            <div class="business">
                <h2>Business 3</h2>
                <p>Category: Services</p>
                <p>Location: 789 Oak St.</p>
                <p>Contact: (555) 345-6789</p>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Local Business Directory</p>
    </footer>
</body>
</html>