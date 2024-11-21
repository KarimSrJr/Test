# Test
Just testing 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The World is Yours</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 20%;
            overflow: hidden; /* Hides overflow text if it moves off the screen */
            background-color: #f3f3f3;
        }

        h1 {
            font-size: 50px;
            color: #4CAF50;
            animation: moveWords 5s infinite alternate;
        }

        @keyframes moveWords {
            0% {
                transform: translateX(100%); /* Start from the right */
            }
            50% {
                transform: translateX(-100%); /* Move to the left */
            }
            100% {
                transform: translateX(100%); /* Return to the right */
            }
        }
    </style>
</head>
<body>
    <h1>The World is Yours</h1>
</body>
</html>

