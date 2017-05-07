<template lang="html">
  <section id="portfolio" class="content-section">
    <div class="portfolio-section">
      <p>멋쟁이 사자처럼 5기</p>
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
</style>
