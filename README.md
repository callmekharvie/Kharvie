<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> tron Blog</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>My Blog</h1>
        <nav>
            <a href="/">Home</a>
            <a href="/about">About</a>
            <a href="/contact">Contact</a>
        </nav>
    </header>

    <main>
        <article>
            <h2>First Blog Post</h2>
            <p>Published: June 16, 2025</p>
            <p>This is my first blog post. I hope you enjoy reading it!</p>
            <a href="/post1">Read More</a>
        </article>
    </main>

    <footer>
        <p>&copy; 2025 My Blog</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background: #555;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav a {
    color: #fff;
    text-decoration: none;
    padding: 0 10px;
}

main {
    padding: 20px;
}

article {
    background: #fff;
    padding: 10px 20px;
    margin-bottom: 20px;
}

footer {
    text-align: center;
    padding: 10px;
    background: #777;
    color: #fff;
}
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-YOUR_PUBLISHER_ID"
     crossorigin="anonymous"></script>
<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-YOUR_PUBLISHER_ID"
     data-ad-slot="YOUR_AD_SLOT_ID"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Blog - First Post</title>
    <meta name="description" content="This is my first blog post about [topic].">
    <link rel="stylesheet" href="style.css">
</head> 
<img src="image.jpg" alt="Description of the image">
from flask import Flask, render_template

app = Flask(__Tron__)

posts = [
    {
        'title': 'First Blog Post',
        'date': 'June 16, 2025',
        'content': 'This is my first blog post. I hope you enjoy reading it!',
        'url': 'post1'
    }
]

@app.route('/')
def home():
    return render_template('index.html', posts=posts)

if __name__ == '__main__':
    app.run(debug=True)
