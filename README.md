<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website</title>
    <style>
        header {
            text-align: center;
            padding: 100px 0;
        }

        section {
            text-align: center;
            padding: 50px 20px;
        }

        footer {
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>

<section>
    <h2>Section Content</h2>
    <p>This is the content of the section.</p>
</section>

</body>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Four Quadrant Layout</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
        }
        .container {
            display: grid;
            grid-template-rows: 50% 50%;
            grid-template-columns: 50% 50%;
            height: 100%;
        }
        .photo {
            grid-row: 1 / span 1;
            grid-column: 1 / span 1;
            background-color: #f0f0f0;
            text-align: center;
        }
        .text {
            grid-row: 1 / span 1;
            grid-column: 2 / span 1;
            background-color: #e0e0e0;
            padding: 20px;
        }
        .empty {
            grid-row: 2 / span 1;
            grid-column: 1 / span 2;
            background-color: #d0d0d0;
        }
        .name-heading {
            text-align: center;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="photo">
        <!-- Placeholder for photo -->
        <img src="kapil.jpg" alt="Your Photo" width="20%" height="20%">
    </div>
    <div class="text">
        <!-- Multiple lines of text -->
        <h1 class="name-heading">Kapil Choudhary</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed eget metus nec massa interdum eleifend. Nulla facilisi. Integer bibendum nisl ut urna ullamcorper aliquet.</p>
        <p>Phasellus tempus mattis elit, a consectetur velit fermentum nec. Fusce eu mi quis ligula laoreet tincidunt. Nam accumsan ligula ut velit ultricies scelerisque.</p>
    </div>
    <div class="empty"></div>
    <div class="empty"></div>
</div>

</body>

</html>
