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
    <h2>Greasy</h2>
    <!-- <div class="form-container">
      <h3>Contact Jesse</h3>
      <form name="contact" method="POST" data-netlify="true">
        <p><label>Your Name:<br /><input label="Your Name" name="name" /></label></p>
        <p><label>Your Email:<br /><input type="email" name="email" /></label></p>
        <p><label>Message:<br /><textarea name="message"></textarea></label></p>
        <p><button type="submit">Send</button></p>
      </form>
    </div> -->
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
  background-color: rgba(255,255,255, 0.66);
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  flex-direction: column;
  max-width: 360px;
  height: 100vh;
  padding: 2rem;
}
h1 {
  color: #111;
  font-size: 3rem;
  margin: 2rem auto 0;
}
h2 {
  color: #111;
  font-size: 2.5rem;
  margin: 0 auto 2rem;
  font-weight: 400;
}
.form-container {
  margin: 0 auto;
}
</style>