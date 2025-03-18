# 🌟 Simple Portfolio Website

## 📌 Description
A clean and minimal personal portfolio webpage built using basic HTML & CSS. Perfect for showcasing skills, projects, and contact information.

## 🎨 Demo Preview (HTML & CSS)/
🔴index.html

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            text-align: center;
        }

        header {
            background-color: #4CAF50;
            padding: 30px;
            color: white;
        }

        section {
            padding: 20px;
        }

        .btn {
            background-color: #4CAF50;
            color: white;
            padding: 10px 25px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            font-size: 16px;
            text-decoration: none;
        }

        .btn:hover {
            background-color: #45a049;
        }
    </style>
</head>

<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <p>Web Developer | Tech Enthusiast</p>
    </header>
    <section>
        <h2>About Me</h2>
        <p>This is a sample portfolio page built using HTML and CSS. It showcases basic web development skills.</p>
        <a href="contact.html" class="btn">Contact</a>
    </section>
</body>

</html>
```

🔴contact.html
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Page</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            text-align: center;
        }

        header {
            background-color: #4CAF50;
            padding: 30px;
            color: white;
        }

        section {
            padding: 40px;
        }

        form {
            max-width: 400px;
            margin: auto;
        }

        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 16px;
        }

        .btn {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 25px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }

        .btn:hover {
            background-color: #45a049;
        }
    </style>
</head>

<body>
    <header>
        <h1>Contact Me</h1>
    </header>
    <section>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>
</body>

</html>
```
