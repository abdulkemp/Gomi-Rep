<template>
  <div>
    <div class="fifth">
      <div class="leftt">
        <div class="left-img">
          <img
            src="https://i.postimg.cc/BZpkSzG6/GOMI-PLASTIC-4-5.webp"
            alt=""
          />
        </div>
      </div>
      <div class="right-text">
        <div class="width">
          <div class="heading">
            <h1>FROM WASTE ⸻ TO BEAUTY</h1>
          </div>
        </div>
        <div class="lower-heading">
          <p>
            Hand-crafted from ‘non recyclable’ waste plastics. Powered by
            second-life lithium batteries.
          </p>
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
                  <p>ABOUT OUR MATERIALS</p>
                </a>
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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.fifth {
  /* width: 100%; */
  display: flex;
  margin-bottom: 7rem;
  margin: 2rem;
}

.leftt {
  width: 50%;
  display: flex;
  justify-content: start;
  align-items: center;
}

.left-img {
  width: 37rem;
  height: 45.8rem;
}

.left-img img {
  width: 100%;
  height: 100%;
}

.right-text {
  width: 60%;
  display: flex;
  justify-content: center;
  align-items: start;
  flex-direction: column;
  gap: 1.5rem;
  padding-left: 5rem;
  font-weight: 100;
}

.heading h1 {
  font-family: "Almarai", sans-serif;
  font-size: 2rem;
}

.width {
  width: 19rem;
}

.lower-heading{
    width: 23rem;
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
</style>