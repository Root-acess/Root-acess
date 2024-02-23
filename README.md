<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        p {
            margin-bottom: 20px;
        }
        .highlight {
            color: #446688;
        }
        .animate {
            animation: fadeIn 2s;
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>
    <h1 class="animate">Welcome to My Project!</h1>
    <p class="animate">This project is a simple example of how to use HTML, CSS, and JavaScript to create an animated and interactive GitHub README file.</p>
    <p class="animate">Here are some of the key features:</p>
    <ul>
        <li class="animate highlight">Animated text and elements</li>
        <li class="animate highlight">Interactive elements using JavaScript</li>
        <li class="animate highlight">Custom styles using CSS</li>
    </ul>
    <script>
        // Example JavaScript code
        const heading = document.querySelector('h1');
        heading.addEventListener('click', () => {
            heading.style.color = '#f00';
        });
    </script>
</body>
</html>
