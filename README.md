<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Simple Webpage</h1>
    </header>

    <section id="main-content">
        <p>This is a simple webpage created with HTML, CSS, and JavaScript.</p>
        <button id="alertButton">Click Me!</button>
    </section>

    <footer>
        <p>&copy; 2025 My Simple Webpage</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

#main-content {
    text-align: center;
    padding: 20px;
}

button {
    padding: 10px 20px;
    background-color: #007BFF;
    color: white;
    border: none;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #0056b3;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
document.getElementById("alertButton").addEventListener("click", function() {
    alert("Button clicked! Welcome to my webpage.");
});
