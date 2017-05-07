<template lang="html">
  <section id="portfolio" class="content-section">
    <div class="portfolio-section">
      <h3><a href="https://likelion.net">LikeLion 5th tutor @Inha Univ.</a></h3>
      <p>2017.01.01 ~ now</p>
      <h3><a href="https://candidaily.com">CandiDaily Project</a></h3>
      <p>2017.04.14 ~ 2017.04.16</p>
      <p></p>
    </div>

  </section>
</template>

<script>
export default {
  name: 'portfolio'
}
</script>

<style lang="css" scoped>
  section {
    background-color: black;
    color: white;
    text-align: center;
  }
  .content-section {
    padding: 100px 0;
  }
  .portfolio-section {
    width: 100%;
    padding: 50px 0;
    text-align: center;
    color: white;
    background: url(/downloads-bg.jpg) no-repeat bottom center scroll;
    background-color: black;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    background-size: cover;
    -o-background-size: cover;
  }
  a {
    margin-right: 20px;
    font-size:30px;
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
</style>
