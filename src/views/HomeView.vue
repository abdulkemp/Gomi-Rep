<!-- <template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script> -->

<template>
  <!-- <ChatBot /> -->
  <div class="home-top" data-aos="zoom-in" data-aos-duration="800">
    
    <h1 class="h1">SOUND NEVER</h1>
    <h1>LOOKED SO GOOD</h1>
    <a href=""
      ><svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="w-6 h-6 arrow"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3"
        />
      </svg>
      <p>DISCOVER OUR SPEAKERS</p>
    </a>
    <video
      src="https://cdn.shopify.com/videos/c/o/v/886fbb75103f412da7ad419d0449e8c5.mp4"
      playsinline="true"
      preload="auto"
      muted="muted"
    ></video>
    <div class="logos">
      <div class="bbc">
        <img
          src="https://i.postimg.cc/GtvhSJFr/pngegg-8.png
        "
          alt=""
        />
      </div>
      <div id="fifth" class="dezeen">
        <img src="https://i.postimg.cc/Lss56PpB/My-project-9.png" alt="" />
      </div>
      <div class="wired">
        <img
          src="https://i.postimg.cc/SQCxTJPN/wired-logo-transparent.png"
          alt=""
        />
      </div>
      <div class="financial">
        <img src="https://i.postimg.cc/C1BKbVdR/My-project-10.png" alt="" />
      </div>
      <div class="fast">
        <img src="https://i.postimg.cc/wvxtNJHB/pngegg-9.png" alt="" />
      </div>
      <div class="design">
        <img src="https://i.postimg.cc/cHDvBH4B/My-project-11.png" alt="" />
      </div>
      <div class="forbes">
        <img
          src="https://i.postimg.cc/V6xkRHbD/forbes-logo-transparent-free-png-1.jpg"
          alt=""
        />
      </div>
    </div>
  </div>
  <Second />
  <Third />
  <Forth />
  <Fifth />
  <Sixth />
  <Seventh />
  <Eight />
  <Footer />
</template>

<script>
import Second from "../components/Second.vue";
import Third from "../components/Third.vue";
import Forth from "../components/Forth.vue";
import Fifth from "../components/Fifth.vue";
import Sixth from "../components/Sixth.vue";
import Seventh from "../components/Seventh.vue";
import Eight from "../components/Eight.vue";
import Footer from "../components/Footer.vue";
// import ChatBot from '../components/ChatBot.vue';
export default {
  components: {
    Second,
    Third,
    Forth,
    Fifth,
    Sixth,
    Seventh,
    Eight,
    Footer,
    // ChatBot
  },
  data() {
    return {
      bgColor: "transparent",
    };
  },
  mounted() {
    window.addEventListener("scroll", this.onScroll);
  },

  methods: {
    onScroll() {
      const scrollTop = window.pageYOffset;
      if (scrollTop > 100) {
        this.bgColor = "black";
      } else {
        this.bgColor = "white";
      }
    },

    beforeDestroy() {
      window.removeEventListener("scroll", this.onScroll);
    },
  },
};
</script>

<style>

.back {
  transition: 5s;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.home-top {
  /* width: 100%; */
  height: 100%;
  padding-top: 80px;
  margin-top: 7rem;
  margin: 2rem;
}

.home-top h1 {
  font-size: 10rem;
  font-family: "Almarai", sans-serif;
  color: black;
}

.h1 {
  margin-bottom: -3rem;
}

.home-top a {
  display: flex;
  justify-content: start;
  align-items: center;
  gap: 10px;
  text-decoration: none;
  color: black;
  font-size: 25px;
  margin-top: -1rem;
}

.arrow {
  margin-left: 5px;
  width: 2rem;
  color: black;
  padding-bottom: 17px;
}

video {
  margin-top: 1rem;
  width: 100%;
}

.logos {
  width: 100%;
  height: 10vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 4rem;
  opacity: 0.5;
  margin-top: 2.6rem;
  margin-bottom: 6rem;
}

.bbc {
  width: 10%;
  height: 2.3rem;
  display: flex;
  justify-content: center;
  align-content: center;
}

.bbc img {
  width: 100%;
  height: 100%;
}

.dezeen {
  width: 10%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-content: center;
}

.dezeen img {
  width: 100%;
  height: 100%;
}

.wired {
  width: 10%;
  height: 2rem;
  display: flex;
  justify-content: center;
  align-content: center;
}

.wired img {
  width: 100%;
  height: 100%;
}

.financial {
  width: 10%;
  height: 2.3rem;
  display: flex;
  justify-content: center;
  align-content: center;
}

.financial img {
  width: 100%;
  height: 100%;
}

.fast {
  width: 10%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-content: center;
}

.fast img {
  width: 100%;
  height: 100%;
}

.design {
  width: 10%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-content: center;
}

.design img {
  width: 100%;
  height: 100%;
}

.forbes {
  width: 10%;
  height: 3rem;
  display: flex;
  justify-content: center;
  align-content: center;
}

.forbes img {
  width: 100%;
  height: 100%;
}
</style>
