---
{"dg-publish":true,"permalink":"/trekking/"}
---

<div class="carousel-container">
  <div class="carousel-track">
    <img src="imagenes/IMG_9298.jpg" alt="Imagen 1">
    <img src="imagenes/IMG_2014.jpg" alt="Imagen 2">
    <img src="imagenes/IMG_9498.jpg" alt="Imagen 3">
    <img src="imagenes/IMG_9491.jpg" alt="Imagen 4">
    <img src="imagenes/IMG_9441.jpg" alt="Imagen 5">
    <img src="imagenes/FullSizeRender.jpg" alt="Imagen 6">
    <img src="imagenes/IMG_9469.jpg" alt="Imagen 7">
    <img src="imagenes/IMG_9412.jpg" alt="Imagen 8">
    <img src="imagenes/IMG_9316.jpg" alt="Imagen 9">
    <img src="imagenes/IMG_8283.jpg" alt="Imagen 10">
    <img src="imagenes/IMG_8281.jpg" alt="Imagen 11">
    <img src="imagenes/IMG_9310.jpg" alt="Imagen 12">
    <img src="imagenes/IMG_9325.jpg" alt="Imagen 13">
    <img src="imagenes/IMG_7609.jpg" alt="Imagen 14">
    <img src="imagenes/IMG_9279.jpg" alt="Imagen 15">
    <img src="imagenes/IMG_9272.jpg" alt="Imagen 16">
    <img src="imagenes/IMG_8266.jpg" alt="Imagen 17">
    <img src="imagenes/IMG_8231.jpg" alt="Imagen 18">
    <img src="imagenes/IMG_7651.jpg" alt="Imagen 19">
    
    <!-- Duplicado para loop infinito -->
    <img src="imagenes/IMG_9298.jpg" alt="Imagen 1">
    <img src="imagenes/IMG_2014.jpg" alt="Imagen 2">
    <img src="imagenes/IMG_9498.jpg" alt="Imagen 3">
    <img src="imagenes/IMG_9491.jpg" alt="Imagen 4">
    <img src="imagenes/IMG_9441.jpg" alt="Imagen 5">
    <img src="imagenes/FullSizeRender.jpg" alt="Imagen 6">
    <img src="imagenes/IMG_9469.jpg" alt="Imagen 7">
    <img src="imagenes/IMG_9412.jpg" alt="Imagen 8">
    <img src="imagenes/IMG_9316.jpg" alt="Imagen 9">
    <img src="imagenes/IMG_8283.jpg" alt="Imagen 10">
    <img src="imagenes/IMG_8281.jpg" alt="Imagen 11">
    <img src="imagenes/IMG_9310.jpg" alt="Imagen 12">
    <img src="imagenes/IMG_9325.jpg" alt="Imagen 13">
    <img src="imagenes/IMG_7609.jpg" alt="Imagen 14">
    <img src="imagenes/IMG_9279.jpg" alt="Imagen 15">
    <img src="imagenes/IMG_9272.jpg" alt="Imagen 16">
    <img src="imagenes/IMG_8266.jpg" alt="Imagen 17">
    <img src="imagenes/IMG_8231.jpg" alt="Imagen 18">
    <img src="imagenes/IMG_7651.jpg" alt="Imagen 19">
  </div>
</div>

<style>
.carousel-container {
  overflow: hidden;
  width: 100%;
  margin: 20px 0;
  border-radius: 10px;
}

.carousel-track {
  display: flex;
  animation: scroll 30s linear infinite;
  width: fit-content;
}

.carousel-track img {
  height: 300px;
  width: auto;
  object-fit: cover;
  margin-right: 15px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

@keyframes scroll {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-50%);
  }
}

.carousel-track:hover {
  animation-play-state: paused;
}
</style>