### Assignment 5.1 — Convert an HTML Page into a Styled Page

**1. `index.html`**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>

    <h1>Welcome to My College</h1>
    <p>This website provides information about our college.</p>
</body>
</html>
```

**2. `style.css`**

```css
body {
    background-color: #f0f4f8;
    color: #333;
    font-family: Arial, sans-serif;
    margin: 20px;
}

h1 {
    color: navy;
    text-align: center;
}

p {
    font-size: 18px;
    line-height: 1.6;
}

nav {
    background-color: navy;
    padding: 15px;
    text-align: center;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 15px;
}

nav a:hover {
    color: yellow;
    text-decoration: underline;
}
```

**Submission:** Save both files in the same folder, open `index.html` with Live Server, and inspect CSS using Chrome DevTools (`F12`).