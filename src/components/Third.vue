<template>
  <div id="third">
    <div class="third">
        <div class="third-h1" data-aos="zoom-in" data-aos-duration="800">
            <h1>
             <span>   STATEMENT SOUNDS </span>⸻ RICH AUDIO, FINE TUNED BY OUR WORLD-RENOWNED ENGINEERS
            </h1>
        </div>
        <div class="img-right" data-aos="zoom-in" data-aos-duration="800">
            <img src="https://i.postimg.cc/BQ7xdTfG/gomispeaker-collection1-web11.webp" alt="">
        </div>
    </div>
    <div class="third2">
        <div class="third-h1" data-aos="zoom-in" data-aos-duration="800">
            <h1>
              <span> THE END OF OBSOLESCENCE </span>  ⸻ CONSCIOUS MODULAR DESIGN MEANS INFINITE REPAIRS AND SOUND THAT LASTS A
            </h1>
        </div>
        <div class="img-right1" data-aos="zoom-in" data-aos-duration="800">
            <h1>LIFETIME</h1>
            <img src="https://i.postimg.cc/Bb0sJqDR/LIFESTYLE-4-5-2880x3600-6ceb8b8c-d084-439c-88d6-cc5af22f7dea-1-1.jpg" alt="">
        </div>
    </div>
  </div>
</template>

<script>
    export default {
       name: 'Third' 
    }
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

#third{
  margin: 2rem;
}

.third{
    /* width: 100%; */
    height: 100%;
    margin-top: 8rem;
    
}
.third2{
    width: 100%;
    height: 100%;
    margin-top: 9rem;
}

.third-h1{
    width: 78%;
}
.third-h1 h1 span {
    font-size: 4.5rem;
    color: black;
    font-weight: bold;
    font-family: "Familjen Grotesk", sans-serif;
  }

.third-h1 h1 {
    font-size: 4.2rem;
    color: rgb(31, 31, 31);
    font-family: "Familjen Grotesk", sans-serif;
  }

  .img-right{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: end;
    align-items: center;
  }
  .img-right1{
    width: 100%;
    height: 80rem;
    display: flex;
    gap: 2rem;
  }

  .img-right1 h1{
    font-size: 4.2rem;
    color: rgb(31, 31, 31);
    font-family: "Familjen Grotesk", sans-serif;
  }

  .img-right1 img{
    width: 100%;
    height: 100%;
  }
  .img-right img{
    width: 51.4%;
    height: 100%;
  }
</style>