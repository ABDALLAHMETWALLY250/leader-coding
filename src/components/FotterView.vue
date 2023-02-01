<template>
  <div class="fields">
    <div class="fotter">
      <p style="margin-bottom: 0" class="copyright txt-c pt-15">
        Made With <i class="fa fa-heart c-main text-danger"></i> By ABDALLAH ©
        2023
      </p>
      <p style="margin-bottom: 0" class="social pt-15">
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-youtube"></i>
        <i class="fa-brands fa-github"></i>
        <i class="fa-brands fa-twitter"></i>
        <i class="fa-brands fa-codepen"></i>
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-solid fa-envelope"></i>
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.fields {
  margin-top: 100px;
}
@media screen and (max-width: 767px) {
  .fotter {
    background: #000;
    color: #fff;
    width: 100%;
    align-items: center;
    text-align: center;
  }
  .txt-c {
    margin-bottom: 0;
  }
  .fa-brands,
  .fa-solid {
    margin-right: 10px;
    margin-bottom: 35px;
    font-size: 30px;
  }
}
@media screen and (min-width: 767px) and (max-width: 1023px) {
  .fotter {
    background: #000;
    color: #fff;
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    text-align: center;
  }
  .txt-c {
    margin-bottom: 35px;
  }
  .fa-brands,
  .fa-solid {
    margin-right: 10px;
    margin-bottom: 35px;
    font-size: 30px;
  }
}
@media screen and (min-width: 1024px) {
  .fotter {
    background: #000;
    color: #fff;
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    text-align: center;
    bottom: 0;
  }
  .txt-c {
    margin-bottom: 35px;
  }
  .fa-brands,
  .fa-solid {
    margin-right: 10px;
    margin-bottom: 35px;
    font-size: 30px;
  }
}

.fa-facebook,
.fa-youtube,
.fa-github,
.fa-twitter,
.fa-codepen,
.fa-instagram,
.fa-envelope {
  background: #333;
  border-radius: 10%;
  padding: 5px;
  cursor: pointer;
}
.fa-facebook:hover,
.fa-twitter:hover,
.fa-envelope:hover {
  background: #0075ff;
  color: #fff;
}
.fa-youtube:hover {
  background: red;
  color: #fff;
}
.fa-github:hover,
.fa-codepen:hover {
  background: #000;
  color: #fff;
}
.fa-instagram:hover {
  background-image: linear-gradient(#d300c5, #f5c33b);
}
</style>
