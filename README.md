<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <input type="color" id="colorPicker">
    <h1>Hexa Code</h1>
    <input type="text" id="box">
    <script>
        document.getElementById("colorPicker").addEventListener('input',()=>{
            let color=document.getElementById("colorPicker").value;
            document.body.style.backgroundColor=color;
            document.getElementById("box").value=color;

        })
    </script>
</body>
</html>
