<template>
  <div id="forth" data-aos="zoom-in" data-aos-duration="800">
    <div class="forth">
      <div class="forthh">
        <div class="forth1">
          <h1>BRING A LITTLE SOUND AND COLOUR INTO YOUR HOME</h1>
        </div>
        <div class="link">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke-width="1.5"
            stroke="currentColor"
            class="w-6 h-6 arrow1"
            style="color: white;"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3"
            />
          </svg>

          <a href="">
            <p>DISCOVER OUR SPEAKERS</p>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Forth",

//   data() {
//     return {
//     bgColor: 'black'
//   }
//   },
//   mounted() {
//     window.addEventListener("scroll", this.onScroll);
//   },

//   methods: {
//     onScroll() {
//     const scrollTop = window.pageYOffset
//     if (scrollTop > 100) {
//       this.bgColor = 'white'
//     } else {
//       this.bgColor = 'black'
//     }
//   },

//   beforeDestroy() {
//   window.removeEventListener('scroll', this.onScroll)
// },
//   },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.forth {
  /* width: 100%; */
  height: 150vh;
  display: flex;
  justify-content: center;
  align-content: center;
  margin-top: 8rem;
  margin-bottom: 8rem;
  flex-direction: column;
  padding: 2rem;
  background-color: black;
  color: white;
  
}
.forth1 {
  width: 73%;
  height: 75%;
}

.forthh {
  width: 100%;
  height: fit-content;
  flex-direction: column;
}


.forth1 h1 {
  font-size: 6.3rem;
  color: white;
  font-family: "Almarai", sans-serif;
  font-weight: bolder;
}

.link {
  width: 100%;
  height: fit-content;
  margin-top: 2rem;
  gap: 8px;
  color: white;
  display: flex;
}

.arrow1 {
  margin-left: 5px;
  width: 2rem;
  color: black;
}

.link a {
  text-decoration: none;
  color: white;
  padding-top: 12px;
  font-size: 25px;
}

.forth1 p {
  color: white;
}
</style>