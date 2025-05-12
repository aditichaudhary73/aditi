# aditi

# Project Title

create an isometric room 
<!DOCTYPE html>
<html>
<head>
<title>Isometric Room</title>
</head>
<body>
<div class="isometric-room">
    <div class="wall-front"></div>
    <div class="wall-left"></div>
    <div class="wall-right"></div>
    <div class="floor"></div>
</div>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
<title>Isometric Room</title>
<style>
  body {
    background-color: #eee;
  }
  .room {
    position: absolute;
    width: 200px;
    height: 150px;
    transform: rotateY(45deg) rotateX(35deg);
    transform-origin: 0 0;
    perspective: 500px; /* Adjust for desired depth */
    border: 1px solid black;
    margin: 50px;
  }
  .wall {
    width: 100%;
    height: 100%;
    background-color: #999;
  }
  .floor {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 20px; /* Example height */
    background-color: #555;
  }
</style>
</head>
<body>
  <div class="room">
    <div class="wall"></div>
    <div class="floor"></div>
  </div>
</body>
</html>
