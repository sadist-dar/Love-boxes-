<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You, Sadist</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #ffe6e6;
        }
        h1 {
            color: #ff3366;
            font-size: 36px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 20px;
        }
        .box {
            width: 120px;
            height: 120px;
            background-color: #ff99aa;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 14px;
            font-weight: bold;
            margin: 5px;
            border-radius: 10px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <h1>I Love You, Sadist ❤️</h1>
    <div class="container" id="boxContainer"></div>

    <script>
        // Function to generate 100 love boxes
        function generateBoxes() {
            const container = document.getElementById("boxContainer");
            for (let i = 0; i < 100; i++) {
                let box = document.createElement("div");
                box.className = "box";
                box.innerText = "I love you, sadist ❤️";
                container.appendChild(box);
            }
        }

        // Call the function on page load
        window.onload = generateBoxes;
    </script>
</body>
</html>
