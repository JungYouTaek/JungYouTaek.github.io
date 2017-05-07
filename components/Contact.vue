<template lang="html">
  <section id="contact" class="content-section">
    <h2>Contact Me</h2>
    <p>Feel free to email me to provide some feedback on my site</p>
    <p>give me suggestions for new project, or to just say hello!</p>
    <p><a href="mailto:jyt9319@gmail.com"><span>jyt9319@gmail.com</span></a>
    </p>
    <ul class="list-inline banner-social-buttons">
        <li>
            <a href="https://takeuu.tistory.com" class="btn btn-default btn-lg"><i class="fa fa-handshake-o fa-fw"></i> <span class="network-name">Blog</span></a>
        </li>
        <li>
            <a href="https://github.com/Jungyoutaek" class="btn btn-default btn-lg"><i class="fa fa-github fa-fw"></i> <span class="network-name">Github</span></a>
        </li>
        <li>
            <a href="#" class="btn btn-default btn-lg"><i class="fa fa-google fa-fw"></i> <span class="network-name">Google</span></a>
        </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'Contact'
}
</script>

<style lang="css">
  section {
    background-color: black;
    color: white;
    padding: 100px;
    text-align: center;
  }
  h2 {
    font-size: 50px;
    font-weight: 700;
    margin-bottom: 30px;
  }
  p {
    font-size: 20px;
  }
  span {
    color: #42DCA3;
  }
  .btn {
    text-transform: uppercase;
    font-family: "Montserrat", "Helvetica Neue", Helvetica, Arial, sans-serif;
    font-weight: 400;
    -webkit-transition: all 0.3s ease-in-out;
    -moz-transition: all 0.3s ease-in-out;
    transition: all 0.3s ease-in-out;
    border-radius: 0;
  }
  .btn-default {
    border: 1px solid #42DCA3;
    color: #42DCA3;
    background-color: transparent;
  }
  .btn-default:hover,
  .btn-default:focus {
    border: 1px solid #42DCA3;
    outline: none;
    color: black;
    background-color: #42DCA3;
  }
  ul {
    margin-top: 30px;
  }
  li {
    padding-top: 10px;
  }
</style>
