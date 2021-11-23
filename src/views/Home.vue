<template>
  <div class="home">
    <div class="container-fluid" id="hero_img">
      <div class="container-fluid" id="hero">
        <p class="h2" id="subtitle">Lorem ipsum dolor sit, amet consectetur!</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style lang="scss">
#hero_img {
  height: 100vh;
  width: 100vw;
  background-image: url("template.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-color: black;
  box-shadow: inset 100vw 0px 0px rgba(0, 0, 0, 0.25);
}
#hero{
  padding: 20vh 0vw 10vh 0vw;

  #subtitle{
    color: white;
  }

}
</style>
