<template>

  <Html lang="en-CA">
      <Head>
        <Title>Jesse Cahill | Greasy</Title>
        <Meta name="description" content="Greasy" />
      </Head>
  </Html>
  <section class="main">
    <div class="content-container">
    <h1>Jesse Cahill</h1>
    <h2><a href="https://vsoschoolofmusic.ca/faculty/jesse-cahill/">[vita@vso]</a></h2>
  </div>
  </section>
</template>

<script setup>
  useMeta({
      meta: [
        { name: 'viewport', content: 'width=device-width, initial-scale=1, maximum-scale=5' }
      ],
      bodyAttrs: {
        class: 'home'
      }
  })
</script>

<style>
* {
  box-sizing: border-box;
  font-family: 'Open Sans', sans-serif;
  font-weight: 700;
}
body {
    background-color: #222;
    margin: 0;
    padding: 0;
}
section.main {
  background-image: url('~/assets/images/jc-bg.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
  height: 100vh;
  width: 100vw;
}
.content-container {
  background: linear-gradient(0deg, rgba(0,0,0,0.85) 0%, rgba(66,66,66,0.85) 100%);
  border: 1px solid #444;
  border-radius: 2rem;
  box-shadow: 0 0 0.5rem 0.25rem rgba(0,0,0, 0.66);
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  flex-direction: column;
  max-width: 360px;
  height: auto;
  padding: 2rem;
  margin: 2rem 2rem auto;
}
h1 {
  text-shadow: 0 0 0.5rem  rgba(0,0,0, 0.85);
  color: #fff;
  font-size: 3rem;
    margin: 0 auto;
}
h2 {
  text-shadow: 0 0 0.5rem  rgba(0,0,0, 0.85);
  color: #fff;
  font-size: 1.75rem;
  font-weight: 400;
  margin: 0 auto;
}
a {
  color: inherit;
}
@media (max-width: 500px) {
  .content-container {
    margin: 2rem auto auto;
    width: 100%;
  }
  h1 {
    font-size: 2rem;
  }
  h2 {
    font-size: 1.5rem;
  }
}
.form-container {
  margin: 0 auto;
}
</style>