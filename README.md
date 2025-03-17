<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Special Proposal</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; margin-top: 50px; }
        button { font-size: 20px; padding: 10px 20px; margin: 10px; cursor: pointer; }
        #no-btn { position: absolute; transition: all 0.3s ease-in-out; }
    </style>
</head>
<body>

    <h1>Will You Collaborate With Me?</h1>
    <button id="yes-btn" onclick="alert('Yay! Let’s build something awesome together! 🚀')">YES</button>
    <button id="no-btn" onmouseover="moveButton()">NO</button>

    <script>
        function moveButton() {
            let x = Math.random() * window.innerWidth * 0.8;
            let y = Math.random() * window.innerHeight * 0.8;
            document.getElementById('no-btn').style.left = x + 'px';
            document.getElementById('no-btn').style.top = y + 'px';
        }
    </script>

</body>
</html>
