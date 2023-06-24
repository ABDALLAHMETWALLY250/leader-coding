<template>
  <div class="html">
    <NavBar />
    <div class="intro-Html">
      <h2>HTML</h2>
      <p>hyper text markup language</p>
    </div>
    <div class="html fields">
      <h4>What is html ?</h4>
      <div class="fields">
        <div class="container">
          <div class="row">
            <div class="col-sm-8">
              <img
                src="https://img.freepik.com/free-icon/html-5_318-566077.jpg?w=2000"
                alt="HTML"
              />
            </div>
            <div class="col-sm-4">
              <ul>
                <li>HTML stands for Hyper Text Markup Language</li>
                <li>
                  HTML is the standard markup language for creating Web pages
                </li>
                <li>HTML describes the structure of a Web page</li>
                <li>HTML consists of a series of elements</li>
                <li>
                  HTML elements tell the browser how to display the content
                </li>
                <li>
                  HTML elements label pieces of content such as "this is a
                  heading", "this is a paragraph", "this is a link", etc.
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  components: {
    NavBar,
  },
};
</script>

<style lang="scss" scoped>
.intro-Html {
  background-image: url("../views/wave-haikei.svg");
  height: 90vh;
  width: 100%;
  background-size: cover;
  background-repeat: no-repeat;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  h2,
  p {
    font-weight: bold;
    color: white;
  }
}
.info {
  display: flex;
  flex-direction: column;
  align-items: center;
  column-gap: 10px;
}
.fields {
  margin-top: 100px;
}
.html {
  height: 100vh;
  h4 {
    font-weight: bold;
    color: #333;
  }
}
.v-sheet {
  // outline: none;
  background-color: transparent;
  border: 1px solid;
}
@media screen and (max-width: 767px) {
  h2 {
    font-size: 80px;
  }
  p {
    font-size: 25px;
  }
  h4 {
    font-weight: bold;
    font-size: 35px;
  }
  .col-sm-8 img {
    display: none;
  }
  .col-sm-8 {
    display: none;
  }
  .col-sm-4 {
    display: grid;
    justify-content: center;
    align-items: center;
    width: 100%;
    row-gap: 25px;
    text-align: left;
  }
  .row {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 50px;
  }
}
@media screen and (min-width: 767px) and (max-width: 1023px) {
  h2 {
    font-size: 85px;
  }
  p {
    font-size: 25px;
  }
  h4 {
    font-weight: bold;
    font-size: 55px;
  }
  .col-sm-8 {
    display: block;
  }
  .col-sm-4 {
    display: grid;
    justify-content: center;
    align-items: center;
    width: 100%;
    row-gap: 25px;
    text-align: left;
    margin-top: 50px;
  }
  .row {
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
@media screen and (min-width: 1024px) {
  h2 {
    font-size: 85px;
  }
  h4 {
    font-weight: bold;
    font-size: 50px;
  }
  p {
    font-size: 25px;
  }
  .col-sm-8 {
    width: 55%;
  }
  .col-sm-4 {
    display: grid;
    justify-content: center;
    align-items: center;
    row-gap: 30px;
    text-align: left;
  }
  .row {
    display: flex !important;
    flex-wrap: nowrap;
    margin-top: 50px;
  }
}
ul {
  display: contents;
}
</style>
