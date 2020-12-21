# stage
<!DOCTYPE html>
<html>
    <head>
        <title>Guitar heros</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="style.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    </head>
    <body>
        <div id="studio">
            <audio controls id="music">
                <source src="./assets/music/music.mp3" type="audio/mpeg">
            </audio>
            <button id="play">Play me</button>
            <div id="score"></div>
            <div id="result"></div>
            <table id="guitar">
                <tr id="line-x">
                    <td id="line-x-1" class=”line”></td>
                    <td id="line-x-2" class=”line”></td>
                    <td id="line-x-3" class=”line”></td>
                    <td id="line-x-4" class=”line”></td>
                </tr>
                <tr id="line-keys">
                    <td id="line-x-1" class=”line text”>A</td>
                    <td id="line-x-2" class=”line text”>Z</td>
                    <td id="line-x-3" class=”line text”>E</td>
                    <td id="line-x-4" class=”line text”>R</td>
                </tr>
            </table>

        </div>
        <script src="main.js"></script>
    </body>
</html>
