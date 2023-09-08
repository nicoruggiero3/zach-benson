<!DOCTYPE html>
<html>
<head>
  <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <img src="https://media.d3.nhle.com/image/private/t_document/prd/eb2li9gxme4fe04gm2ed.jpg" alt="Zach Benson" style="width:400px;height:400px;">
    </div>
    <div class="flip-card-back">
    <img
src="https://media.d3.nhle.com/image/private/t_document/prd/zbekcefazasaucaifhg6.jpg" alt="Zach Benson bio"
style="width:400px;height:400px;">
    </div>
  </div>
</div>
<style>
.flip-card {
  background-color: transparent;
  width: 300px;
  height: 200px;
  border: 10px solid #f1f1f1;
  perspective: 1000px; 
}
.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}
.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}
.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; 
  backface-visibility: hidden;
}
.flip-card-front {
  background-color: #bbb;
  color: black;
}
.flip-card-back {
  background-color: blue;
  color: gold;
  transform: rotateY(180deg);
}
</style>
</head>
<body>
</body>
</html>

