<html lang="en">
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Change color</title>
    <link rel="stylesheet" type="text/css" href="styal.css">
</head>

<body>
    <div class="bg-wrapper">
        <a onclick="bgcolor('red')"  id="red">#ff0000</a>
        <a onclick="bgcolor('black')"  id="black">#026d40</a>
        <a onclick="bgcolor('blue')"  id="blue">#f1e205</a>
    </div>
    <div class="banner-text">
        <h3>Animation</h3>
    </div>
    <script>
        function bgcolor(id){
            document.body.style.backgroundColor = document.getElementById(id).innerHTML

        }

    </script>
</body>

</html>
