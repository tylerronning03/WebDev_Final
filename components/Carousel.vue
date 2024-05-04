<template>
    <div class="carousel w-full ">
        <div id="slide1" class="carousel-item relative w-full overflow-hidden h-[40vh]">
          <img src="public/Blueprint.png" class="w-screen h-full object-cover" />
          <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
            <a href="#slide4" class="btn btn-circle">❮</a> 
            <a href="#slide2" class="btn btn-circle">❯</a>
          </div>
        </div> 
        <div id="slide2" class="carousel-item relative w-screen overflow-hidden h-[40vh]">
          <img src="public/UE53.png" class="w-screen h-full object-cover" />
          <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
            <a href="#slide1" class="btn btn-circle">❮</a> 
            <a href="#slide3" class="btn btn-circle">❯</a>
          </div>
        </div> 
        <div id="slide3" class="carousel-item relative w-screen overflow-hidden h-[40vh]">
          <img src="public/SQL.png" class="w-screen h-full object-cover" />
          <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
            <a href="#slide2" class="btn btn-circle">❮</a> 
            <a href="#slide4" class="btn btn-circle">❯</a>
          </div>
        </div> 
        <div id="slide4" class="carousel-item relative w-screen overflow-hidden h-[40vh]">
          <img src="public/UE54.png" class="w-screen h-full object-cover" />
          
          <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
            <a href="#slide3" class="btn btn-circle">❮</a> 
            <a href="#slide5" class="btn btn-circle">❯</a>
          </div>
        </div> 
        <div id="slide5" class="carousel-item relative w-screen overflow-hidden h-[40vh]">
          <img src="public/CSharp2.png" class="w-screen h-full object-cover" />
          <div class="absolute flex justify-between transform -translate-y-1/2 left-5 right-5 top-1/2">
            <a href="#slide4" class="btn btn-circle">❮</a> 
            <a href="#slide1" class="btn btn-circle">❯</a>
          </div>
        </div>
  </div>
</template>