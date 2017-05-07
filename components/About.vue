<template lang="html">
  <section id="about" class="content-section">
  <h2>About Me</h2>
  <p>I'll be <span>Front-end Developer</span></p>
  <p>Wanna be <span>special</span> and <span>Different</span> one</p>
  <p>When your legs don't work like they used to before
  And I can't sweep you off of your feet
  Will your mouth still remember the taste of my love
  Will your eyes still smile from your cheeks</p>
  <p>And darling I will be loving you 'til we're 70
  And baby my heart could still fall as hard at 23
  And I'm thinking 'bout how people fall in love in mysterious ways
  Maybe just the touch of a hand
  Oh me I fall in love with you every single day
  And I just wanna tell you I am</p>
  </section>
</template>

<script>
export default {
  name: 'about'
}
</script>

<style lang="css" scoped>
  section {
    background-color: black;
    color: white;
    text-align: center;
    padding:0 150px;
  }
  .content-section {
    padding: 100px;
  }
  h2 {
    text-transform: uppercase;
    font-weight: 700;
    font-size: 50px;
  }
  p {
    line-height: 1.5;
    font-size: 20px;
  }
  span {
    color: #42DCA3;
  }
</style>
