<template>
  <div>
    <div class="fo">
      <!-- <img src="https://i.postimg.cc/6q8tbVJJ/footer.webp" alt=""> -->
      <div class="foot">
        <div class="top-foot">
          <input type="text" placeholder="MAILING LIST SIGNUP" />
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
        </div>
        <div class="lower-top-foot">
          <p>
            Be the first to know about new collections and exclusive offers. By
            submitting your email address you agree to our
            <a href="https://gomi.design/policies/privacy-policy"
              >privacy policy</a
            >.
          </p>
        </div>
      </div>
      <div class="bottom-foot">
        <div class="bottom-left-foot">
          <div class="left-foot">
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
              <p>NEED A REPAIR?</p>
            </a>
          </div>
          <div class="list-foot">
            <ul>
              <li>TERMS AND CONDITIONS</li>
              <li>WARRENTIES</li>
              <li>PRIVACY POLICY</li>
            </ul>
          </div>
        </div>
        <div class="row">
          <div class="col coll">
            <div class="he">
              <p>DISCOVER</p>
            </div>
            <div class="links">
              <ul>
                <li>HOME</li>
                <li>COLLECTION ONE</li>
                <li>LIMITED DROPS</li>
                <li>ABOUT THE STUDIO</li>
                <li>OUR MATERIALS</li>
                <li>COLLABORATIONS</li>
                <li>GOMI FOR LIFE</li>
                <li>JOURNAL</li>
              </ul>
            </div>
          </div>
          <div class="col coll">
            <div class="he">
              <p>INFO</p>
            </div>
            <div class="links">
              <ul>
                <li>SHIPPING</li>
                <li>PRESS KIT</li>
                <li>REPAIR POLICY</li>
                <li>REFUND POLICY</li>
                <li>BATTERY PARTNERS</li>
                <li>WHOLESALE</li>
              </ul>
            </div>
          </div>
          <div class="col coll">
            <div class="he">
              <p>QUESTIONS</p>
            </div>
            <div class="links">
              <ul>
                <li>FAQS</li>
                <li>CONTACT US</li>
              </ul>
            </div>
          </div>
          <div class="col coll">
            <div class="he">
              <p>FOLLOW US</p>
            </div>
            <div class="links">
              <ul>
                <li>INSTAGRAM</li>
                <li>FACEBOOK</li>
                <li>YOUTUBE</li>
                <li>MAILING LIST</li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="gomi">
      <div class="gomi-image">
        <img
          src="https://i.postimg.cc/jqnzJGmc/Logogomipng-800x382-1.png"
          alt=""
        />
      </div>
    </div>
    <div class="back"></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.fo {
  height: 100%;
  margin-left: 2rem;
  margin-right: 2rem;
  
}
.back{
  width: 100%;
  height: 30vh;
  background-image: url(https://i.postimg.cc/6q8tbVJJ/footer.webp);
  background-attachment: fixed;
  background-size: cover;
}

.gomi-image{
  width: 100%;
  height: 80vh;
}

.gomi-image img{
  width: 100%;
  height: 100%;
  background-attachment: fixed;
}

.gomi {
  width: 100%;
  height: 80vh;
 
  /* background-repeat: no-repeat; */
}

.gomi-bottom{
  width: 100%;
}
.fo img{
  width: 100%;
  
}

.top-foot {
  width: 100%;
  display: flex;
  justify-content: space-between;
  font-size: 4.4rem;
  border-bottom: 2px solid black;
}

.top-foot input {
  border: transparent;
  outline: none;
  background-color: #f7f7f7;
  font-family: "Almarai", sans-serif;
}

.top-foot input:focus::placeholder {
  color: transparent;
}

.top-foot input::placeholder {
  border: none;
  color: black;
  font-family: "Almarai", sans-serif;
}

.top-foot svg {
  width: 6rem;
}

.lower-top-foot {
  width: 30.5rem;
  font-family: "Almarai", sans-serif;
  color: black;
  margin-top: 1rem;
}

.lower-top-foot a {
  color: black;
  font-family: "Almarai", sans-serif;
}

.bottom-foot {
  width: 100%;
  height: 45vh;
  display: flex;
}

.bottom-left-foot {
  width: 50%;
  height: 85%;
  display: flex;
  justify-content: end;
  align-items: start;
  flex-direction: column;
}

.left-foot {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;
}

.left-foot a p {
  font-size: 1.4rem;
  padding-top: 1rem;
  color: black;
}

.left-foot a {
  text-decoration: none;
}
.left-foot a:hover {
  text-decoration: underline;
  color: black;
}

.row {
  width: 50%;
  height: 100%;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}

.row .coll {
  width: 25%;
  height: 75%;
}

.links {
  width: 100%;
  height: 100%;
}

.links ul {
  display: flex;
  justify-content: start;
  flex-direction: column;
  gap: 5px;
  font-size: 13px;
}

ul {
  padding-left: 0;
  color: black;
}

ul li {
  list-style: none;
  font-family: "Quicksand", sans-serif;
}

.he {
  width: 100%;
  height: 10%;
}
</style>
