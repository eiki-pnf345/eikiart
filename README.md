<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minimalist Art Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Minimalist Art Store</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#gallery">ギャラリー</a></li>
            <li><a href="#about">作家について</a></li>
            <li><a href="#contact">お問い合わせ</a></li>
        </ul>
    </nav>
    <section id="gallery">
        <h2>ギャラリー</h2>
        <!-- ここに作品の画像を追加 -->
    </section>
    <section id="about">
        <h2>作家について</h2>
        <p>作家の紹介やアートについての説明</p>
    </section>
    <section id="contact">
        <h2>お問い合わせ</h2>
        <form>
            <label for="name">名前:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">メールアドレス:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">メッセージ:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">送信</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Minimalist Art Store</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #fff;
    color: #000;
}

header, footer {
    background-color: #000;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #000;
}

nav ul li {
    display: inline;
    margin: 0 1em;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2em;
    border-bottom: 1px solid #ccc;
}

form {
    max-width: 600px;
    margin: 0 auto;
}

form label {
    display: block;
    margin: 0.5em 0 0.2em;
}

form input, form textarea {
    width: 100%;
    padding: 0.5em;
    margin-bottom: 1em;
    border: 1px solid #ccc;
    border-radius: 4px;
}

form button {
    padding: 0.5em 2em;
    background-color: #000;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background-color: #444;
}
