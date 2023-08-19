<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <!-- <ChatBot /> -->
  <NavBar />
  <router-view/>
  <div class="chat fixed-bottom">
      <div class="chatBot">
        <img src="https://i.postimg.cc/q7Hh45hp/Untitled1.png" alt="" />
      </div>
    </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
// import ChatBot from './components/ChatBot.vue'
export default{
  name: 'App',
  components: {
    NavBar,
    // ChatBot
  },
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  overflow: hidden;
  /* text-align: center;
  color: #2c3e50; */
}

.chat {
  
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: end;
  align-items: end;
  flex-direction: column;
  padding-right: 1rem;
  padding-bottom: 3rem;
  position: absolute;
  position: fixed;
  z-index: 100;
}

.chatBot {
  width: 4rem;
  height: 4rem;
  background-color: black;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  /* position: fixed; */
}

.chatBot img {
  width: 2.5rem;
  height: 2.5rem;
  border-radius: 50%;
}

/* 
nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
