# Agnieszka-shop
# Tworzymy prosty projekt HTML z podstawową strukturą strony podobnej do sklepu internetowego.

project_path = "/mnt/data/Aga_Shop"
html_content = """
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aga - Sklep internetowy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            display: block;
        }
        nav a:hover {
            background-color: #555;
        }
        .hero {
            text-align: center;
            padding: 50px;
            background: #eee;
        }
        .hero h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product {
            background: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            text-align: center;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
            margin-bottom: 10px;
        }
        .product h2 {
            font-size: 1.2rem;
            margin: 0 0 10px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color
              : #333;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Witamy w sklepie Aga</h1>
    </header>
    <nav>
        <a
