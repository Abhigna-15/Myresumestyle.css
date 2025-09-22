# Myresumestyle.css
/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

/* Body Styling */
body {
    background-color: #f5f7fa;
    color: #333;
    line-height: 1.6;
    padding: 20px;
    max-width: 900px;
    margin: auto;
}

/* Header Styling */
header {
    text-align: center;
    padding: 20px;
    border-bottom: 2px solid #ccc;
}

header h1 {
    font-size: 2.2em;
    color: #2c3e50;
    margin-bottom: 10px;
}

header img {
    border-radius: 50%;
    width: 120px;
    height: 120px;
    object-fit: cover;
    margin: 10px 0;
    border: 3px solid #3498db;
}

header ul {
    list-style: none;
    margin-top: 10px;
}

header ul li {
    margin: 5px 0;
    font-size: 1em;
}

header a {
    color: #3498db;
    text-decoration: none;
    font-weight: bold;
}

header a:hover {
    text-decoration: underline;
}

/* Section Styling */
section {
    margin: 20px 0;
    padding: 15px;
    background: #ffffff;
    border-radius: 8px;
    box-shadow: 0px 2px 6px rgba(0,0,0,0.1);
}

section h2 {
    font-size: 1.5em;
    margin-bottom: 10px;
    color: #2c3e50;
    border-bottom: 2px solid lightskyblue;
    display: inline-block;
    padding-bottom: 3px;
}

section ul {
    list-style: disc;
    padding-left: 20px;
    margin-top: 10px;
}

section li {
    margin-bottom: 8px;
}

section p {
    margin-bottom: 8px;
}

/* Footer Styling */
footer {
    margin-top: 30px;
    padding: 15px;
    text-align: right;
    font-size: 0.95em;
    background: white;
    border-top: 2px solid white;
    border-radius: 8px;
}

footer li {
    list-style: none;
    margin-bottom: 5px;
}
