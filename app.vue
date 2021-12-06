<template>
  <Html lang="en-CA">
      <Head>
        <Title>Jessa Cahill | Greasy</Title>
        <Meta name="description" content="Greasy" />
      </Head>
  </Html>

  <section class="main">
    <h1>jessecahill.com</h1>
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
  justify-content: center;
  height: 100vh;
  width: 100vw;
}
h1 {
  color: #fff;
  margin: 4rem auto;
}
</style>