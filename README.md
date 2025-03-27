<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Example</title>
</head>
<body>
  <!-- Change Text -->
  <p id="text">Hello, world!</p>
  <button onclick="changeText()">Change Text</button>

  <!-- Change Style -->
  <p id="style">This is a paragraph.</p>
  <button onclick="changeStyle()">Change Style</button>

  <script>
    function changeText() {
      document.getElementById('text').innerText = "Text changed!";
    }

    function changeStyle() {
      document.getElementById('style').style.color = "red";
    }
  </script>
</body>
</html>.

