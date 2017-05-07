<template lang="html">
  <div>
    <nav class="gnb">
      <nuxt-link to="#page-top"><span class="title">TakeU</span></nuxt-link>
      <div class="menu">
        <nuxt-link to="#about">About</nuxt-link>
        <nuxt-link to="#portfolio">Portfolio</nuxt-link>
        <nuxt-link to="#contact">Contact</nuxt-link>
      </div>
    </nav>
    <header class="intro">
      <div class="intro-body">
        <h1>TakeU's Site</h1>
        <p>Youtaek Jung, 24</p>
        <p>Incheon, South Korea</p>
        <p>Inha Univ.</p>
        <a href="#about" class="btn btn-circle">
          <i class="fa fa-angle-double-down" aria-hidden="true"></i>
        </a>
      </div>

    </header>
  </div>
</template>

<script>
export default {
  name: 'intro'
}
</script>

<style scoped>
.intro {
  display: table;
  width: 100%;
  height: auto;
  padding: 100px 0;
  text-align: center;
  color: white;
  background: url(/intro-bg.jpg) no-repeat bottom center scroll;
  background-color: black;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  background-size: cover;
  -o-background-size: cover;
}
.intro .intro-body {
  display: table-cell;
  vertical-align: middle;
}
.gnb {
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 3.5em;
}
.title {
  display: block;
  margin-left: 40px;
  font-size: 30px;
  color: white;
}
.menu {
  display: flex;
  text-transform: uppercase;
}
a {
  margin-right: 20px;
  font-size: 14px;
  color: white;
  text-decoration: none;
  padding-top: 2px;
  padding-bottom: 2px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  transition: color .25s;
  font-weight: 400;
  line-height: normal;
}
a:hover {
  color: #333;
}
.btn-circle {
  width: 70px;
  height: 70px;
  margin: 15px 0 0;
  padding: 7px 16px;
  border: 2px solid white;
  border-radius: 100% !important;
  font-size: 40px;
  color: white;
  background: transparent;
}
.btn-circle:hover,
.btn-circle:focus {
  outline: none;
  color: white;
  background: rgba(255, 255, 255, 0.1);
}
/* header */
header {
  position: flex;
  justify-content: center;
  align-items: center;
}
header h1 {
  font-size: 100px;
  font-weight: 700;
  text-transform: uppercase;
  margin-bottom: 30px;
}
header p {
  font-size: 26px;
}
</style>
