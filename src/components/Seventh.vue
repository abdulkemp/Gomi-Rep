<template>
    <div>
        <div class="seventh">
            <div class="top-part">
                <h1>
                    COLLECTION

                    ⸻ ONE
                </h1>
            </div>
            <div class="caro">
                <div id="carouselExampleSlidesOnly" class="carousel slide hei" data-bs-ride="carousel">
                    <div class="carousel-inner in">
                        <div class="he">
                            <div class="carousel-item item active">
                                <div class="desc">
                                    <p>ULTRAVIOLET</p>
                                </div>
                                <div class="speaker">
                                    <img src="https://i.postimg.cc/3NfbSCSQ/GOMI-SKU-LILAC-RT-transparent.webp" alt="">
                                </div>
                            </div>
                            <div class="carousel-item item">
                                <div class="desc">
                                    <p>PANTHER</p>
                                </div>
                                <div class="speaker">
                                    <img src="https://i.postimg.cc/0QdTfS19/GOMI-SKU-PANTHER-RT-transparent-6c060e10-56bc-42ef-9736-154a050cffac.webp" alt="">   
                                </div>
                            </div>
                            <div class="carousel-item item">
                                <div class="desc">
                                    <p>AVALANCHE</p>
                                </div>
                                <div class="speaker">
                                    <img src="https://i.postimg.cc/D0wMPYcc/GOMI-SKU-WHITE-RT-transparent-cb58e9b0-f985-4616-82f5-ef91350e0536.webp" alt="">   
                                </div>
                            </div>
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
.seventh {
    width: 100%;
    height: 100%;
    padding-bottom: 6rem;
}

.top-part {
    width: 40%;
    height: 30%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding-left: 2rem;
    padding-top: 6rem;
}

.top-part h1 {
    font-size: 5.4rem;
    font-family: "Almarai", sans-serif;
}
.caro{
    height: 70%;
}

.speaker{
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.speaker img{
    width: 80%;
    height: 30rem;
}

.desc{
    padding-left: 2rem;
}

.desc p{
    font-size: 1.3rem;
    font-family: "Almarai", sans-serif;
}

.whole{
  background-color: #f7f7f7;
}
</style>