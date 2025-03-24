---
layout: default
title: Home
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .header {
            background: #0073e6;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .search-bar {
            margin: 20px auto;
            width: 50%;
            display: flex;
            justify-content: center;
        }
        .search-bar input {
            width: 80%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px 0 0 5px;
        }
        .search-bar button {
            padding: 10px;
            border: 1px solid #0073e6;
            background: #0073e6;
            color: white;
            border-radius: 0 5px 5px 0;
            cursor: pointer;
        }
        .search-bar button:hover {
            background: #005bb5;
        }
        .hero {
            padding: 50px;
            background: #f4f4f4;
        }
        .button {
            background: #0073e6;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
        }
        .button:hover {
            background: #005bb5;
        }
    </style>
</head>
<body>
    <div class="header">My Simple Website</div>
    <div class="search-bar">
        <input type="text" placeholder="Search...">
        <button>Go</button>
    </div>
    <div class="hero">
        <h1>Welcome to My Website</h1>
        <p>This is a simple and functional home page.</p>
        <a href="#" class="button">Learn More</a>
    </div>
</body>
</html>
