<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <img
        src="https://thumbs.dreamstime.com/b/vector-logo-coding-companies-company-199205353.jpg"
        alt="Coding"
      />
      <h2>
        <router-link to="/">
          <a class="navbar-brand" href="#">Leader Coding</a></router-link
        >
      </h2>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <router-link to="/" exact
            ><li class="nav-item">
              <a
                class="nav-link hvr-bob hvr-underline-from-left active"
                style="color: white"
                aria-current="page"
                href="#"
                >Home</a
              >
            </li></router-link
          >
          <router-link to="/html"
            ><li class="nav-item">
              <a class="nav-link hvr-bob hvr-underline-from-left" href="#"
                >HTML</a
              >
            </li></router-link
          >
          <router-link to="/html"
            ><li class="nav-item">
              <a class="nav-link hvr-bob hvr-underline-from-left" href="#"
                >CSS</a
              >
            </li></router-link
          >
          <router-link to="/html"
            ><li class="nav-item">
              <a class="nav-link hvr-bob hvr-underline-from-left" href="#"
                >JavaScript</a
              >
            </li></router-link
          >
          <router-link to="/html"
            ><li class="nav-item">
              <a class="nav-link hvr-bob hvr-underline-from-left" href="#"
                >BootStrap</a
              >
            </li></router-link
          >
          <router-link to="/html"
            ><li class="nav-item">
              <a class="nav-link hvr-bob hvr-underline-from-left" href="#"
                >SASS</a
              >
            </li></router-link
          >
          <router-link to="/html"
            ><li class="nav-item">
              <a class="nav-link hvr-bob hvr-underline-from-left" href="#"
                >Jquery</a
              >
            </li></router-link
          >
          <router-link to="/html"
            ><li class="nav-item">
              <a class="nav-link hvr-bob hvr-underline-from-left" href="#"
                >Vue</a
              >
            </li></router-link
          >
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
@media screen and (max-width: 767px) {
  .navbar-expand-lg {
    background-color: #333;
    border-bottom: 1px solid black;
    position: fixed;
    left: 0;
    right: 0;
    z-index: 999;
    a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    h2 a {
      font-size: 25px;
      text-align: center;
    }
  }
}
@media screen and (min-width: 767px) and (max-width: 1023px) {
  .navbar-expand-lg {
    background-color: #333;
    border-bottom: 1px solid black;
    position: fixed;
    left: 0;
    right: 0;
    z-index: 999;
    a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    h2 a {
      font-size: 25px;
      text-align: center;
    }
  }
}
@media screen and (min-width: 1024px) {
  .navbar-expand-lg {
    background-color: #0075ff;
    border-bottom: 1px solid black;
    position: fixed;
    left: 0;
    right: 0;
    z-index: 999;
    a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    h2 a {
      font-size: 25px;
      text-align: center;
    }
  }
}
.navbar-toggler {
  background-color: white;
}
img {
  width: 60px;
  height: 60px;
  object-fit: cover;
  border-radius: 50%;
  margin-right: 4px;
}
</style>
