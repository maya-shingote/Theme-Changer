# Theme-Changer
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mode Changer</title>
    <style>
        body {
            background-color: black;
            color: white;

        }

        .mydark {
            background-color: white;
            color: black;
        }
    </style>
    <script>
        const changeMode = () => {
            let mybody = document.body;
            mybody.classList.toggle('mydark');

        }

    </script>
</head>

<body>
    <h2  style="color: brown; text-align: center;">light Mode to Dark Mode</h2>
    <p style="color: aqua; justify-content: center;">we are working on Theme Changer </p>
    <button onClick="changeMode()"> Change Mode</button>
</body>

</html>

THis is easy THeme changer code file written  with 3 line of arrow function.
#HTML
#CSS
#JAVASCRIPT
