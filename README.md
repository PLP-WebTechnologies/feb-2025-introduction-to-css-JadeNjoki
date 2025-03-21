**index.html**
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Webpage</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking external CSS -->
</head>
<body>

    <header>
        <h1 class="title">Welcome to My Styled Page</h1>
    </header>

    <section>
        <p id="intro">This is a simple webpage with external CSS styling.</p>
        <img src="https://www.pexels.com/photo/1234567/" alt="Sample Image" class="styled-image">
    </section>

    <div class="content-box">
        <h2>About Styling</h2>
        <p>CSS allows us to style HTML elements with colors, fonts, margins, padding, and more.</p>
    </div>

</body>
</html>

**style.css**
/* General body styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    text-align: center;
    margin: 20px;
}

/* Styling the header */
.title {
    color: #333;
    font-size: 28px;
    margin-bottom: 10px;
}

/* Styling paragraph with ID */
#intro {
    font-size: 18px;
    color: #555;
    padding: 10px;
    border: 2px solid #007BFF;
    margin: 10px auto;
    width: 50%;
    border-radius: 10px;
}

/* Styling an image */
.styled-image {
    width: 300px;
    height: auto;
    border: 3px solid #007BFF;
    padding: 5px;
    margin-top: 15px;
    border-radius: 8px;
}

/* Styling a div */
.content-box {
    background-color: white;
    padding: 20px;
    margin: 20px auto;
    width: 60%;
    border: 2px solid #333;
    border-radius: 10px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

