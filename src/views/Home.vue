<template>
  <div class="home">
    <section class="hero is-fullheight is-primary">
      <div class="hero-body">
        <div class="container">
          <div class="columns">
            <div class="column is-6 has-text-centered">
              <h1 class="title has-text-black">unze</h1>
              <p class="subtitle has-text-black">Consultoria de TI</p>
              <br>
              <p class="has-text-black">
                Entre em contato
                pelo e-mail <a href="mailto:hildorjunior@gmail.com">hildorjunior@gmail.com</a>
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
.hero {
  background-image: url('../assets/i-2.svg');
  background-repeat: no-repeat;
  background-size: 40%;
  background-position: 90%;
  @media screen and (max-width: 768px) {
    background-image: none;
  }
}
.title {
  font-size: 8em;
}
</style>
