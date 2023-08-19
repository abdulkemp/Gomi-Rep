<template>
    <div>
        <div class="sixth">
            <div id="carouselExampleSlidesOnly" class="carousel slide hei" data-bs-ride="carousel">
                <div class="carousel-indicators indica">
                    <!-- <button type="button" ></button> -->
                    <div class="button-img">
                        <img src="https://i.postimg.cc/Lss56PpB/My-project-9.png" alt=""
                            data-bs-target="#carouselExampleSlidesOnly" data-bs-slide-to="0" class="active"
                            aria-current="true" aria-label="Slide 1">
                    </div>
                    <div class="button-img">
                        <img src="https://i.postimg.cc/wvxtNJHB/pngegg-9.png" alt=""
                            data-bs-target="#carouselExampleSlidesOnly" data-bs-slide-to="1" aria-label="Slide 2">
                    </div>
                    <div class="button-img">
                        <img src="https://i.postimg.cc/V6xkRHbD/forbes-logo-transparent-free-png-1.jpg" alt=""
                            data-bs-target="#carouselExampleSlidesOnly" data-bs-slide-to="2" aria-label="Slide 3">
                    </div>
                    <div class="button-img">
                        <img src="https://i.postimg.cc/SQCxTJPN/wired-logo-transparent.png" alt=""
                            data-bs-target="#carouselExampleSlidesOnly" data-bs-slide-to="3" aria-label="Slide 4">
                    </div>
                    <!-- <button type="button" ></button> -->
                    <!-- <button type="button" ></button> -->
                    <!-- <button type="button" ></button> -->
                </div>
                <div class="carousel-inner in">
                    <div class="he">
                    <h1>PRESS</h1>
                    <div class="carousel-item item active">
                        <p class="" alt="">“RECYCLED DESIGN IS MORE BEAUTIFUL THAN IT’S EVER BEEN”
                            DEZEEN</p>
                    </div>
                    <div class="carousel-item item">
                        <p class="" alt="">“A PORTABLE BLUETOOTH SPEAKER USING PLASTIC WASTE THAT IS DEEMED
                            NON-RECYCLABLE”
                            FAST COMPANY</p>
                    </div>
                    <div class="carousel-item item">
                        <p class="" alt="">“THIS STARTUP IS TURNING A SEASIDE TOWN'S PLASTIC WASTE INTO
                            SPEAKERS”
                            FORBES</p>
                    </div>
                    <div class="carousel-item item">
                        <p class="" alt="">“GOMI SPEAKER, THE LOUDSPEAKER MADE FROM PLASTIC WASTE”
                            WIRED</p>
                    </div>
                </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.in {
    width: 70%;
    height: 100%;
    text-align: center;
    /* border: 3px solid red; */
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 3rem;
    margin-bottom: 10rem;
    flex-direction: column;
}

.he{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column; 
}

.in h1{
    font-size: 1.2rem;
    font-family: "Almarai", sans-serif;
}

.item {
    width: 47rem;
    height: 20rem;
    /* border: 2px solid green; */
}
.item p {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: "Almarai", sans-serif;
}



.sixth {
    margin-top: 7rem;
    width: 100%;
    height: 110vh;
    background-color: rgba(133, 127, 127, 0.132);
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.hei{
    height: 100%;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    /* border: 1px solid yellow; */
    margin: 4rem;
}

.indica {
    width: 100%;
    /* border: 2px solid black; */
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 3rem;
    padding-bottom: 4rem;

}

.indica .button-img {
    width: 10rem;
    height: 2.5rem;
}

.button-img img {
    width: 100%;
    height: 100%;
    background-color: transparent;
}
</style>