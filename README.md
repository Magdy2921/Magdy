<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A Heartfelt Apology</title>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Color Palette */
        :root {
            --background-color: #f7f7f7;
            --primary-color: #e74c3c;
            --secondary-color: #c0392b;
            --accent-color: #f9e79f;
            --text-color: #333;
            --header-background: #e74c3c;
            --section-background: #ffffff;
            --footer-background: #c0392b;
        }

        body {
            font-family: 'Roboto', sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
            margin: 0;
            padding: 0;
            transition: all 0.3s ease-in-out;
        }

        header {
            text-align: center;
            background-color: var(--header-background);
            padding: 40px;
            margin-bottom: 20px;
            color: #ffffff;
            animation: fadeInDown 1s ease-in-out;
        }

        header h1 {
            font-family: 'Pacifico', cursive;
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        header h2 {
            font-size: 1.8em;
            margin-bottom: 20px;
        }

        main {
            width: 80%;
            margin: 0 auto;
            animation: fadeInUp 1s ease-in-out;
        }

        section {
            margin: 20px 0;
            padding: 30px;
            background-color: var(--section-background);
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }

        section:hover {
            transform: translateY(-5px);
        }

        section h3 {
            color: var(--primary-color);
            font-size: 1.5em;
            margin-bottom: 15px;
        }

        section p {
            font-size: 1.2em;
            color: var(--text-color);
            line-height: 1.8;
            margin-bottom: 20px;
        }

        blockquote {
            font-family: 'Pacifico', cursive;
            font-size: 1.4em;
            text-align: center;
            margin: 20px auto;
            color: var(--secondary-color);
        }

        footer {
            text-align: center;
            background-color: var(--footer-background);
            padding: 20px;
            margin-top: 20px;
            color: #ffffff;
            font-size: 1.2em;
            animation: fadeInUp 1s ease-in-out;
        }

        /* Animations */
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>A Heartfelt Apology</h1>
        <h2>Dear Mohammed Ali, I’m Truly Sorry</h2>
    </header>

    <main>
        <section id="apology">
            <h3>From the Bottom of My Heart</h3>
            <p>I deeply regret my actions and words. I realize how much they have hurt you, and I sincerely apologize for any pain I have caused.</p>
            <p>I hope you can find it in your heart to forgive me.</p>
        </section>

        <section id="reflection">
            <h3>What I’ve Learned</h3>
            <p>This experience has taught me the importance of understanding and kindness. I’ve reflected on my behavior, and I am committed to making positive changes.</p>
        </section>

        <section id="personal-note">
            <h3>To Mohammed Ali</h3>
            <p>Mohammed Ali, I value our relationship deeply. I want to move forward, stronger and wiser, with your forgiveness.</p>
            <blockquote>"The weak can never forgive. Forgiveness is the attribute of the strong." - Mahatma Gandhi</blockquote>
        </section>
    </main>

    <footer>
        <p>Thank you for reading, and I hope we can move forward together.</p>
    </footer>
</body>
</html>
