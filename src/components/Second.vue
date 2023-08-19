<template>
  <div class="second">
    <div class="second-h1" data-aos="zoom-in" data-aos-duration="800">
      <h3>
        <span> ONE OF ONE</span> ⸻ OUR SIGNATURE MARBLING MAKES EVERY SPEAKER
        BEAUTIFULLY
      </h3>
    </div>
    <div class="second-part" data-aos="zoom-in" data-aos-duration="800">
      <h1>UNIQUE</h1>
      <div class="img-side">
        <img
          src="https://i.postimg.cc/bN4C07gK/GOMI-CLOSEUP-RT-3b3f0dc5-793a-48bc-aa7b-f6eb2ce70809.webp"
          alt=""
        />
        <div class="text">
            <p>
                collection one <span> AVALANCHE</span>
            </p>
        </div>
      </div>
    </div>
    <div class="second-part2" data-aos="zoom-in" data-aos-duration="800">
      <div class="img-side2">
        <img
          src="https://i.postimg.cc/m2TxCh31/BACK-4-3-2880x2160-dab749eb-1565-4efc-b71d-93d0a05814a8.webp"
          alt=""
        />
        <div class="text">
            <p>
                collection one <span> ULTRAVIOLET</span>
            </p>
        </div>
      </div>
    </div>
    <div class="second-part3" data-aos="zoom-in" data-aos-duration="800">
      <div class="img-side3">
        <img
          src="https://i.postimg.cc/d3ZpPqN2/LIFESTYLE-8-5-2880x1800-b3c8734b-da7d-46d5-8bc5-2258189fdbd8.webp"
          alt=""
        />
        <div class="text">
            <p>
                collection one <span> PANTHER</span>
            </p>
        </div>
      </div>
    </div>
    
  </div>
</template>

<script>
export default {
  name: "Second",
};


</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.second {
  /* width: 100%; */
  height: 100%;
  animation: fadeIn 2s;
  margin: 2rem;
}

.second-h1 h3 span {
  font-size: 4.5rem;
  color: black;
  font-weight: bold;
  font-family: "Familjen Grotesk", sans-serif;
}

.second-h1 {
  width: 80%;
}

.second-h1 h3 {
  font-size: 4.5rem;
  color: rgb(31, 31, 31);
  font-family: "Familjen Grotesk", sans-serif;
}

.second-part {
  display: flex;
  gap: 2rem;
  width: 100%;
  height: 100%;
}

.second-part img {
  width: 100%;
  height: 100%;
}

.second-part h1 {
  font-size: 4.5rem;
  color: rgb(31, 31, 31);
  font-family: "Familjen Grotesk", sans-serif;
  height: fit-content;
  margin-top: -1rem;
}

.img-side {
  width: 100%;
  display: flex;
  flex-direction: column;
}
.second-part2{
    width: 100%;
    height: 100%;
    margin-bottom: 10px;
}
.second-part3{
    width: 100%;
    height: 130vh;
}
.second-part3 img{
    width: 100%;
    height: 100%;
    background-size: cover;
    background-repeat: no-repeat;
}

.img-side2 {
    margin-top: 10px;
  width: 60%;
  display: flex;
  flex-direction: column;
}

.text{
  display: flex;
  align-items: center;
  font-family: "Familjen Grotesk", sans-serif;
  height: 7vh;
}

.text p span{
    font-size: 1.3rem;
    font-family: "Familjen Grotesk", sans-serif;
    font-weight: 600;
}

@keyframes fadeIn {
    0% { opacity: 0; }
    100% { opacity: 1; }
  }

</style>