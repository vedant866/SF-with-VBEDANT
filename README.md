# SF-with-VBEDANT
SF from is study friend friend
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    <h1>Welcome to My Website!</h1>
<p>This is a simple website made using HTML and CSS.</p>

</header>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home">
        <h2>Home</h2>
        <p>This is my first website created using HTML, CSS, and JavaScript.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>I am a student learning web development!</p>
    </section>

    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
document.getElementById('quiz-form').addEventListener('submit', function(event) {
    event.preventDefault();
    let score = 0;
    const answers = {
        q1: 'a',
        q2: 'b',
    };

    const formData = new FormData(event.target);
    for (const [name, value] of formData) {
        if (answers[name] === value) {
            score++;
        }
    }

    alert('Your score: ' + score + '/' + Object.keys(answers).length);
});
