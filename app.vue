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
    <h2>~ Greasy ~</h2>
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
  background-color: rgba(0,0,0, 0.66);
  border: 4px solid #fff;
  border-radius: 2rem;
  box-shadow: 0 0 0.5rem  rgba(0,0,0, 0.66);
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
  color: #fff;
  font-size: 3rem;
  margin: 1rem auto 0;
}
h2 {
  color: #fff;
  font-size: 2.5rem;
  margin: 0 auto 1rem;
  font-weight: 400;
}
@media (max-width: 500px) {
  .content-container {
    width: 100%;
  }
  h1 {
    font-size: 2rem;
    margin: 0 auto;
  }
  h2 {
    font-size: 1.5rem;
    margin: 0 auto;
  }
}
.form-container {
  margin: 0 auto;
}
</style>