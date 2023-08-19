<template>
  <div>
    <nav>
      <div class="con fixed-top" data-aos="zoom-in" data-aos-duration="800">
        <div class="left">
          <ul>
            <li>
              <a href="">SPEAKERS</a>
            </li>
            <li>
              <a href="#fifth">ABOUT THE STUDIO</a>
            </li>
            <li>
              <a href="">LIMITED DROPS</a>
            </li>
          </ul>
        </div>
        <div class="middle">
          <h3>gomi</h3>
        </div>
        <div class="right">
          <ul>
            <li>
              <a href="">GOMI FOR LIFE</a>
            </li>
            <li>
              <a href="">CART</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "navbar",
};
</script>

<style>
.con {
  width: 100%;
  margin-top: 1rem;
  margin-bottom: 1rem;
  display: flex;
  justify-content: center;
  align-content: center;
}
.left{
    display: flex;
    justify-content: start;
    width: 100%;
    align-content: center;
}
.right{
    display: flex;
    justify-content: end;
    width: 100%;
    align-content: center;
    padding-right: 2rem;
}

.middle h3{
    margin-top: 4px;
    font-size: 1.88rem;
    font-weight: bolder;
    font-family: 'Montserrat', sans-serif;

}

ul{
    display: flex;
    justify-content: center;
    align-content: center;
    gap: 1.5rem;
    height: 100%;
    padding-top: 0.7rem;
}

ul li a{
    text-decoration: none;
    color: black;
    font-weight: 700;
    font-size: 15px;
}


ul li {
  list-style: none;
  font-family: "Almarai", sans-serif;
}

</style>