<!DOCTYPE html>
HIIIII!!
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ghost Animation</title>
</head>
<body>
    <svg id="canvas" viewbox="0 0 2000 1000"></svg>
    <script>
        let canvas = document.getElementsByTagName("svg")[0];
        
        let ghosts = [];
        let colors = ["red", "green", "blue", "yellow", "cyan", "magenta", "black", "purple", "orange"];
        let eyeRadius = 20;
        let pupilRadius = 10;
        let headRadius = 60;
        let bodyWidth = 2 * headRadius;
        let bodyHeight = 100;
        let eyeSpacing = 25; //from center of head

        //You'll need to create two event listeners.

        /* You'll need a click event listener on the canvas that draws a randomly
        colored ghost at the precise location of the click and places a JavaScript
        reference to that ghost into the ghosts array*/

        /* You'll need a mousemove listener on the canvas that makes the eyes
        of each ghost in the ghosts array move in the direction of the current
        mouse coordinates */
    </script>
</body> 
</html>
