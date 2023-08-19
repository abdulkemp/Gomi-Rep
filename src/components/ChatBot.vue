<template>
    <!-- <div class="chat">
        <div class="chatBot">
            <img src="https://i.postimg.cc/q7Hh45hp/Untitled1.png" alt="">
        </div>
    </div> -->
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    .chat{
        width: 100%;
        height: 100vh;
        display: flex;
        justify-content: end;
        align-items: end;
        flex-direction: column;
        padding-right: 1rem;
        padding-bottom: 3rem;
        position: fixed;
        z-index: 100;
    }

    .chatBot{
        width: 4rem;
        height: 4rem;
        background-color: black;
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 50%;
    }

    .chatBot img{
        width: 2.5rem;
        height: 2.5rem;
        border-radius: 50%;
    }
</style>