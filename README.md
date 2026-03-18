# coloured-boxes

h1{
  text-align:center;
}


body{
   background-color : #f4f4f4;
}

.color-box{
  width:60px;
  height:60px;
  padding:10px;
  margin:20px;
  border-radius: 10px;
   display: flex;
   gap: 10px; 
  }

.color1{
  background-color: #00FF00;
}

.color2{
  background-color: rgb(104, 4, 104)
;
}

.color3{
  background-color: orange;
}

.color4{
  background-color: hsl(60, 60%, 30%);
}

.color5{
  background-color: red;
}


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Colored Boxes</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<h1>Colored Boxes</h1>
<div class="color-grid">
    <div class="color-box  color1"></div>
     <div class="color-box  color2"></div>
      <div class="color-box  color3"></div>
       <div class="color-box  color4"></div>
        <div class="color-box  color5"></div>
</div>
</body>
</html>
