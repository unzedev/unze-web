<template>
  <div class="home">
    <section class="hero is-fullheight">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column is-12">
              <p class="subtitle">Agência Digital</p>
              <h1 class="title">unze</h1>
              <br>
              <p>
                Entre em contato e faça sua empresa decolar:
                 <a href="mailto:hildorjunior@gmail.com">hildorjunior@gmail.com</a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Home',
};
</script>

<style lang="scss" scoped>
@import '../assets/variables.scss';
.hero {
  background-image: url('../assets/rocket-bg.jpg');
  background-size: cover;
  background-position-y: 95%;
  border: 15px solid $primary;
  .title {
    font-size: 6.5em;
    color: $primary;
    text-shadow: 3px 3px 0px $link;
    margin-bottom: 0;
    font-weight: normal;
  }
  .subtitle {
    color: hsl(215, 22%, 95%);
    margin-bottom: -20px;
  }
  p, a {
    color: hsl(215, 22%, 95%);
  }
}
</style>
