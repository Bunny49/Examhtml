<!-- index.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarah's Blog</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
        <h1>Sarah's Blog</h1>
        <img src="logo.png" alt="Logo">
    </header>

    <!-- Main Content Section -->
    <main>
        <!-- Audio and Video Elements -->
        <audio controls>
            <source src="background-music.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
        <video controls width="500" height="300">
            <source src="introduction.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>

        <!-- Iframe for YouTube Video -->
        <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>

        <!-- Table Element -->
        <table>
            <tr>
                <th>Column 1</th>
                <th>Column 2</th>
            </tr>
            <tr>
                <td>Cell 1</td>
                <td>Cell 2</td>
            </tr>
        </table>

        <!-- Form Element -->
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name"><br><br>
            <label for="comment">Comment:</label>
            <textarea id="comment" name="comment"></textarea><br><br>
            <input type="submit" value="Submit">
        </form>

        <!-- Image Element -->
        <img src="image.jpg" alt="Image">

        <!-- Lists -->
        <ol>
            <li>Ordered List Item 1</li>
            <li>Ordered List Item 2</li>
        </ol>
        <ul>
            <li>Unordered List Item 1</li>
            <li>Unordered List Item 2</li>
        </ul>

        <!-- Links -->
        <a href="#">Link to another page</a>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 Sarah's Blog</p>
        <ul>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Twitter</a></li>
            <li><a href="#">Instagram</a></li>
        </ul>
    </footer>
</body>
</html>





/* styles.css */

/* Global Styles */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f9f9f9;
}

/* Header Styles */
header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

header nav ul li {
    margin-right: 20px;
}

header nav a {
    color: #fff;
    text-decoration: none;
}

header h1 {
    font-size: 24px;
    margin-bottom: 10px;
}

header img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin: 20px auto;
}

/* Main Content Styles */
main {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2em;
}

/* Audio and Video Styles */
audio, video {
    width: 100%;
    height: 300px;
    margin-bottom: 20px;
}

/* Iframe Styles */
iframe {
    width: 100%;
    height: 315px;
    margin-bottom: 20px;
    border: none;
}

/* Table Styles */
table {
    border-collapse:
