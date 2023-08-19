<template>
  <div class="whole">
    <div class="eight">
      <div class="cen">
        <div class="left-cen">
          <div class="text-cen">
            <h1>GOMI FOR LIFE</h1>
            <h2>
              Throw-away culture is broken. Our modular design is for life.
            </h2>
          </div>
          <div class="lower-links">
            <div class="link">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="w-6 h-6 arrow1"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3"
                />
              </svg>

              <a href="">
                <p>ABOUT REPAIRS</p>
              </a>
            </div>
          </div>
        </div>
        <div class="right-cen">
            <div class="block">
                <div class="rotate">
                    <img src="https://i.postimg.cc/J4YgCdSk/Black-White-Mix-GM002.jpg" alt="">
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>

.whole{
  background-color: #f7f7f7;
}
.eight {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  /* margin-bottom: ; */
}

.cen {
  width: 100%;
  height: 45vh;
  margin: 2rem;
  background-color: rgba(133, 127, 127, 0.132);
  display: flex;
}

.left-cen {
  width: 35%;
  display: flex;
  justify-content: center;
  align-items: start;
  flex-direction: column;
  height: 100%;
  padding: 2rem;
}

.left-cen h2{
  font-size: 2rem;
  font-family: "Almarai", sans-serif;
}
.left-cen h1{
  font-size: 2rem;
  font-family: "Almarai", sans-serif;
}
.link {
  width: 100%;
  height: fit-content;
  gap: 8px;
  color: black;
  display: flex;
}

.arrow1 {
  width: 2rem;
  color: black;
}

.link a {
  text-decoration: none;
  color: black;
}

.right-cen{
    width: 65%;
    height: 100%;
    display: flex;
    justify-content: end;
    align-items: center;
}

.right-cen .block{
    width: 40%;
    height: 100%;
    margin-bottom: 12rem;
    display: flex;
    justify-content: end;
    padding-right: 1.5rem;
}

.rotate{
    border: 8px solid;
    border-color: transparent black transparent black;
    border-radius: 50%;
    padding: 0.5rem;
    width: 14rem;
    height: 14rem;
    
}

.rotate img{
    border-radius: 50%;
    width: 100%;
    height: 100%;
}
</style>
