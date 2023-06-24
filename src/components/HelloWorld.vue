<template>
  <div class="intro">
    <h1>Welcome In Leader Coding</h1>
    <p>
      The Leader Coding Academy is an educational platform that provides many
      web development paths with detailed interactive explanations in English,
      and study plans with tests to ensure understanding of the code and
      application to it.
    </p>
    <div class="form">
      <input
        type="text"
        id="text"
        placeholder="Search In The Leader Coding Academy "
      />
      <button type="button" id="search" class="btn btn-primary text-center">
        Search
      </button>
    </div>
  </div>
  <div class="fields">
    <h3>educational tracks</h3>
    <div class="cards container">
      <div class="cardone">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            height="200"
            src="https://elzero.org/wp-content/themes/elzero/imgs/home-tracks/frontend-track.svg"
          >
          </v-img>
          <v-card-text class="text-center">
            <div><a href="http://"> Front End Track</a></div>
          </v-card-text>
        </v-card>
      </div>
      <div class="cardtwo">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            height="200"
            src="https://elzero.org/wp-content/themes/elzero/imgs/home-tracks/javascript-track.svg"
          >
          </v-img>
          <v-card-text class="text-center">
            <div><a href="http://"> Full Stack Track</a></div>
          </v-card-text>
        </v-card>
      </div>
      <div class="cardthree">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            height="200"
            src="https://elzero.org/wp-content/themes/elzero/imgs/home-tracks/python-track.svg"
          >
          </v-img>
          <v-card-text class="text-center">
            <div><a href="http://"> Python Web Developer Track</a></div>
          </v-card-text>
        </v-card>
      </div>
    </div>
  </div>

  <div class="fields">
    <h3>Study plans</h3>
    <div class="cards container">
      <v-container class="bg-surface-variant">
        <v-row no-gutters>
          <v-col order="6">
            <v-sheet class="pa-2 ma-2">
              <img
                src="https://elzero.org/wp-content/themes/elzero/era/imgs/plans/cpp.png"
                alt="C++"
              />
            </v-sheet>
          </v-col>
          <v-col order="6">
            <v-sheet class="pa-2 ma-2">
              <img
                src="https://elzero.org/wp-content/themes/elzero/era/imgs/plans/html.png"
                alt="HTML"
              />
            </v-sheet>
          </v-col>
          <v-col order="6">
            <v-sheet class="pa-2 ma-2">
              <img
                src="https://elzero.org/wp-content/themes/elzero/era/imgs/plans/css.png"
                alt="CSS"
              />
            </v-sheet>
          </v-col>
          <v-col order="6">
            <v-sheet class="pa-2 ma-2">
              <img
                src="https://elzero.org/wp-content/themes/elzero/era/imgs/plans/javascript.png"
                alt="JavaScript"
              />
            </v-sheet>
          </v-col>
          <v-col order="11">
            <v-sheet class="pa-2 ma-2">
              <img
                src="https://elzero.org/wp-content/themes/elzero/era/imgs/plans/sass.png"
                alt="SASS"
              />
            </v-sheet>
          </v-col>
          <v-col order="12">
            <v-sheet class="pa-2 ma-2">
              <img
                src="https://elzero.org/wp-content/themes/elzero/era/imgs/plans/typescript.png"
                alt="TS"
              />
            </v-sheet>
          </v-col>
        </v-row>
      </v-container>
    </div>
  </div>

  <div class="fields">
    <h3>Latest Front-End Apps</h3>
    <div class="cards container">
      <div class="cardone">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            src="https://img.youtube.com/vi/T5QyLcmcMJ4/maxresdefault.jpg"
          >
          </v-img>
          <v-card-text class="text-center">
            <div><a href="http://"> Create quiz app</a></div>
          </v-card-text>
        </v-card>
      </div>
      <div class="cardtwo">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            src="https://img.youtube.com/vi/wZ90BnBbRsg/maxresdefault.jpg"
          >
          </v-img>
          <v-card-text class="text-center">
            <div><a href="http://"> how to use currency API</a></div>
          </v-card-text>
        </v-card>
      </div>
      <div class="cardthree">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            src="https://img.youtube.com/vi/Nxny2QvEIm0/maxresdefault.jpg"
          >
          </v-img>
          <v-card-text class="text-center">
            <div><a href="http://"> create page scroll progress</a></div>
          </v-card-text>
        </v-card>
      </div>
      <div class="cardthree">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            src="https://img.youtube.com/vi/ZFb_eaYtWwY/maxresdefault.jpg"
          >
          </v-img>
          <v-card-text class="text-center">
            <div><a href="http://"> Create Hangman Game </a></div>
          </v-card-text>
        </v-card>
      </div>
    </div>
  </div>

  <div class="fields">
    <h3>Latest articles added</h3>
    <div class="cards container">
      <div class="cardone">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            src="https://elzero.org/wp-content/uploads/2022/11/symbols-names.png"
          >
          </v-img>
          <v-card-text class="text-center">
            <div>
              <a
                href="https://elzero.org/characters-names-used-in-programming/"
              >
                The names of the tags that you use in the programming world</a
              >
            </div>
          </v-card-text>
        </v-card>
      </div>
      <div class="cardtwo">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            src="https://elzero.org/wp-content/uploads/2022/09/hardest-programming-language.png"
          >
          </v-img>
          <v-card-text class="text-center">
            <div>
              <a href="http://">
                The most difficult programming language Is programming
                difficult?</a
              >
            </div>
          </v-card-text>
        </v-card>
      </div>
      <div class="cardthree">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            src="https://elzero.org/wp-content/uploads/2022/11/developer-terms.png"
          >
          </v-img>
          <v-card-text class="text-center">
            <div>
              <a href="http://">
                Some terms in the world of technology and their meaning</a
              >
            </div>
          </v-card-text>
        </v-card>
      </div>
      <div class="cardthree">
        <v-card class="mx-auto">
          <v-img
            class="align-end text-white"
            src="https://elzero.org/wp-content/uploads/2022/10/good-pc-to-learn-programming.png"
          >
          </v-img>
          <v-card-text class="text-center">
            <div>
              <a href="http://"> The right device to learn programming </a>
            </div>
          </v-card-text>
        </v-card>
      </div>
    </div>
  </div>

  <div class="fields">
    <h3>What's New</h3>
    <div class="cards container">
      <div class="card w-50 mr-3 mb-3">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="http://">Add a hosting page</a>
          </h5>
          <p class="card-text text-left">
            A page dealing with hosting has been added and contains explanations
            of hosting and servers
          </p>
        </div>
      </div>
      <div class="card w-50 mr-3 mb-3">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="http://">
              The study plans for the president have been added with some
              features</a
            >
          </h5>
          <p class="card-text text-left">
            Study plans have been added to the main page with a change to the
            Contact Us page
          </p>
        </div>
      </div>
    </div>
    <div class="cards container">
      <div class="card w-50">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="">Add previous and next to new sections</a>
          </h5>
          <p class="card-text text-left">
            On all pages whose design has been changed, you will find at the
            bottom of the article
          </p>
        </div>
      </div>
      <div class="card w-50 mr-3 mb-3 bae mt-3">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href=""
              >Change the design of Python sections and apply to HTML + CSS</a
            >
          </h5>
          <p class="card-text text-left">
            The design of the Python and Application sections has been changed
            to HTML + CSS
          </p>
        </div>
      </div>
    </div>
  </div>

  <div class="fields">
    <h3>The last written explanations</h3>
    <div class="cards container">
      <div class="card w-50 mr-3 mb-3" style="border-left: 1px solid #464646">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="http://" class="text-dark"
              >Explanation of showing the Custom Excerpt only</a
            >
          </h5>
          <p
            class="card-text text-center bg-dark text-light"
            style="width: 85px; border-radius: 10px"
          >
            wordpress
          </p>
        </div>
      </div>

      <div class="card w-50 mr-3 mb-3" style="border-left: 1px solid #f7df1e">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="" class="text-dark"
              >Get ASCII Code from Characters and vice versa</a
            >
          </h5>
          <p
            class="card-text text-center text-dark fw-bold"
            style="
              width: 100px;
              border-radius: 10px;
              background: #f7df1e;
              padding: 0 3px;
            "
          >
            JavaScript
          </p>
        </div>
      </div>

      <div class="card w-50 mr-3 mb-3" style="border-left: 1px solid #337ab7">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="" class="text-dark">
              Get ASCII Code from Characters and vice versa</a
            >
          </h5>
          <p
            class="card-text text-center text-light"
            style="width: 85px; border-radius: 10px; background: #0075ff"
          >
            python
          </p>
        </div>
      </div>

      <div class="card w-50" style="border-left: 1px solid #4f5b93">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="" class="text-dark"
              >Get ASCII Code from Characters and vice versa</a
            >
          </h5>
          <p
            class="card-text text-center text-light"
            style="width: 85px; border-radius: 10px; background: #4f5b93"
          >
            php
          </p>
        </div>
      </div>
    </div>
  </div>
  <div class="">
    <div class="cards container">
      <div
        class="card w-50 mr-3 mb-3 bat"
        style="border-left: 1px solid #4f5b93"
      >
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="http://" class="text-dark"
              >Count the number of lines inside the file in more than one way</a
            >
          </h5>
          <p
            class="card-text text-center text-light"
            style="width: 85px; border-radius: 10px; background: #4f5b93"
          >
            php
          </p>
        </div>
      </div>
      <div class="card w-50 mr-3 mb-3" style="border-left: 1px solid #4f5b93">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="http://" class="text-dark">
              Get the current file name with the extension in more than one
              way</a
            >
          </h5>
          <p
            class="card-text text-center text-light"
            style="width: 85px; border-radius: 10px; background: #4f5b93"
          >
            php
          </p>
        </div>
      </div>
      <div class="card w-50 mr-3 mb-3" style="border-left: 1px solid #464646">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="http://" class="text-dark">
              Hide the update message inside the control panel for users only</a
            >
          </h5>
          <p
            class="card-text text-center bg-dark text-light"
            style="width: 85px; border-radius: 10px"
          >
            wordpress
          </p>
        </div>
      </div>

      <div class="card w-50" style="border-left: 1px solid #f7df1e">
        <div class="card-body">
          <h5 class="card-title text-left">
            <a href="" class="text-dark">
              Check whether the elements of the array are all the same
              element</a
            >
          </h5>
          <p
            class="card-text text-center text-dark fw-bold"
            style="
              width: 100px;
              border-radius: 10px;
              background: #f7df1e;
              padding: 0 3px;
            "
          >
            JavaScript
          </p>
        </div>
      </div>
    </div>
  </div>
  <br /><br /><br />

  <div class="fields">
    <h3>Various random questions</h3>
    <div class="container">
      <div class="row">
        <div class="col-sm-8">
          <img
            src="https://elzero.org/wp-content/themes/elzero/imgs/questions.svg"
            alt="img"
          />
        </div>
        <div class="col-sm-4">
          <a href="">Why are there many programming languages?</a>
          <a href=""
            >How do I know the technologies used in a particular site?</a
          >
          <a href=""
            >Should I care about the English language before I learn
            programming?</a
          >
          <a href=""
            >How is the right to all the technologies that workers appear?</a
          >
          <a href=""> What is the content of the JS Bootcamp course?</a>
          <a href="">Can I study programming besides my high school studies?</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.intro {
  height: 100vh;
  width: 100%;
  background-color: #0075ff;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  p {
    font-size: 20px;
    font-weight: bold;
    padding: 20px;
    color: #fff;
  }
  .form {
    width: 80%;
    padding: 20px;
  }
}

a {
  text-transform: capitalize;
  font-size: 15px;
  font-weight: bold;
}

.fields h3 {
  width: 100%;
  text-align: center;
  /* padding: 10px 0 0 60px; */
  text-transform: capitalize;
  color: #333;
  font-weight: bold;
  font-size: 30px;
}
.fields {
  margin-top: 100px;
}
@media screen and (max-width: 767px) {
  .intro .form {
    width: 100%;
    padding: 20px;
  }
  h1 {
    font-size: 35px;
    font-weight: bolder;
    color: #fff;
  }

  #text {
    background: #fff;
    width: 100%;
    padding: 20px;
    border-radius: 10px;
    color: #000;
    outline: none;
    border: none;
    position: relative;
    display: block;
    &:focus {
      box-shadow: 0 0 20px 5px #000;
    }
  }
  #search {
    background: #333;
    width: 85px;
    padding: 10px;
    border-radius: 10px;
    color: #fff;
    position: absolute;
    right: 25px;
    height: 43px;
    margin-top: 5px;
  }
  .cards {
    width: 100%;
    text-align: -webkit-center;
    // padding: 20px;
  }
  .cardone,
  .cardtwo,
  .cardthree {
    box-shadow: 0 0 20px;
    margin-left: 10px;
    margin-top: 20px;
    border-radius: 15px;
  }
  .w-50 {
    width: 100% !important;
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
  .bat {
    margin-top: 30px;
  }
  .row {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 50px;
  }
}

@media screen and (min-width: 767px) and (max-width: 1023px) {
  .intro .form {
    width: 100%;
    padding: 20px;
  }
  h1 {
    font-size: 50px;
    font-weight: bolder;
    color: #fff;
  }

  #text {
    background: #fff;
    width: 100%;
    padding: 20px;
    border-radius: 10px;
    color: #000;
    outline: none;
    border: none;
    position: relative;
    &:focus {
      box-shadow: 0 0 20px 5px #000;
    }
  }
  #search {
    width: 85px;
    padding: 10px;
    border-radius: 10px;
    color: #fff;
    position: absolute;
    right: 25px;
    height: 42px;
    margin-top: 10px;
  }
  .cards {
    width: 100%;
    text-align: -webkit-center;
    // padding: 20px;
  }
  .cardone,
  .cardtwo,
  .cardthree {
    box-shadow: 0 0 20px;
    margin-left: 10px;
    margin-top: 20px;
    border-radius: 15px;
  }
  .w-50 {
    width: 100% !important;
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
    margin-top: 50px;
  }
  .row {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .bat {
    margin-top: 30px;
  }
}

@media screen and (min-width: 1024px) {
  h1 {
    font-size: 50px;
    font-weight: bolder;
    color: #fff;
  }
  .intro .form {
    width: 100%;
    padding: 20px;
  }
  #text {
    background: #fff;
    width: 100%;
    padding: 20px;
    border-radius: 10px;
    color: #000;
    outline: none;
    border: none;
    position: relative;
    &:focus {
      box-shadow: 0 0 20px 5px #000;
    }
  }
  #search {
    width: 85px;
    padding: 10px;
    border-radius: 10px;
    color: #fff;
    position: absolute;
    right: 25px;
    height: 43px;
    margin-top: 10px;
  }
  .cards {
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
  .bae {
    margin-left: 30px;
  }
  .cardone,
  .cardtwo,
  .cardthree {
    box-shadow: 0 0 20px;
    width: 50%;
    margin-left: 10px;
    margin-top: 20px;
    border-radius: 15px;
  }
  .col-sm-8 img {
    width: 100%;
    height: 50vh;
    margin-top: 50px;
  }
  .col-sm-4 {
    display: grid;
    justify-content: center;
    align-items: center;
    row-gap: 25px;
    text-align: left;
  }
  .row {
    display: flex !important;
    flex-wrap: nowrap;
    margin-top: 50px;
  }
}
img {
  width: 64px;
  border: none;
  height: 64px;
}
a:hover {
  color: #0075ff;
}
</style>
