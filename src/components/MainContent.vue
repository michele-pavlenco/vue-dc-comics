<template>
  <main>
    <div class="main-first"></div>
    <div class="main-second">
      <div class="container">
        <CardsContent />
      </div>
    </div>
  </main>
</template>

<script>
import CardsContent from "./CardsContent.vue";
export default {
  name: "MainContent",
  components:{
    CardsContent
  }
};
</script>

<style scoped>
.main-first {
  background-image: url(../assets/immagini/jumbotron.jpg);
  background-size: cover;
  height: 300px;
}
.main-second {
background-color: hsl(0deg 0% 11%);
}
</style>
