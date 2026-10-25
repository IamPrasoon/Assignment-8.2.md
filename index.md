
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Image Gallery</title>
<style>
body { font-family: Arial; text-align: center; }
.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 15px;
    padding: 20px;
}
.gallery-item img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 10px;
}
</style>
</head>
<body>
<h1>My Image Gallery</h1>
<div class="gallery">
    <div class="gallery-item"><img src="images/1.jpg" alt="Mountain landscape"></div>
    <div class="gallery-item"><img src="images/2.jpg" alt="Green forest"></div>
    <div class="gallery-item"><img src="images/3.jpg" alt="Ocean beach"></div>
    <div class="gallery-item"><img src="images/4.jpg" alt="City skyline"></div>
    <div class="gallery-item"><img src="images/5.jpg" alt="Flower garden"></div>
    <div class="gallery-item"><img src="images/6.jpg" alt="Sunset sky"></div>
    <div class="gallery-item"><img src="images/7.jpg" alt="Waterfall"></div>
    <div class="gallery-item"><img src="images/8.jpg" alt="Snowy mountains"></div>
</div>
</body>
</html>
