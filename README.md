<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Intro Website</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #5c0a0a;
            color: white;
            line-height: 1.6;
        }
        header {
            text-align: center;
            padding: 50px 20px;
            background-color: #3d0505;
        }

        header h1 {
            margin-bottom: 10px;
            font-size: 42px;
        }

        header p {
            font-size: 18px;
        }
        
        .picture {
        display: block;
        width: 250px;
        height: auto;
        margin: 0 auto 20px;
        border: 4px solid white;
        border-radius: 10px;
        }

        section {
            background-color: #751414;
            padding: 25px;
            margin-bottom: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }

        section h2 {
            color: white;
            border-bottom: 2px solid white;
            padding-bottom: 8px;
        }
        footer {
            text-align: center;
            padding: 25px;
            background-color: #3d0505;
            margin-top: 40px;
        }
        @media (max-width: 600px) {
            header h1 {
                font-size: 32px;
            }

            section {
                padding: 20px;
            }
        }
    </style>
</head>

<body>

    <header>
        <img src="https://res.cloudinary.com/ddwbso0cz/image/upload/v1789061987/20260910_133705_rjz7cs.jpg" alt="Picture" class="picture">

        <h1>Derrick Black</h1>
        <p>Programming and Web Development Student</p>
    </header>

    <main>

        <section>
            <h2>About Me</h2>
            <p>
                My name is Derrick. I have a hobby of playing videos games and browsing the internet. I have an interest in
                technology and am learning about making websites.
            </p>
        </section>

        <section>
            <h2>Web Design Experience</h2>
            <p>
                My experience with web design and development is from last school year where I learned the basics of web design through HTML, CSS, and Java.
            </p>
        </section>

        <section>
            <h2>What I Hope to Learn</h2>
            <p>
                I hope to learn more advanced features of web design to improve my creativity.
            </p>
        </section>

        <section>
            <h2>My Future Goals</h2>
            <p>
                In the future, I would like to use these skills I acquire  for some sort of job that requires creativity. Being a website designer would be one of those potential jobs I could do.
            </p>
        </section>
</body>
</html>
