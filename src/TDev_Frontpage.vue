<template>
  <div class="wrapper">
    <!-- JM Contribute start (9/12/2020) -->
    <contentdesign/>
    <div class="img-wrapper">
      <img src="./assets/large_syncmethod.png" alt="logo" width="20%">
    </div>
    <h1>Core Team starts here.</h1>

    <!-- JM Contribute end (9/12/2020) -->
  </div>
</template>

<script>
import contentdesign from "./components/Content.vue";
export default {
  name: "TDev_Frontpage",
  components: {
    contentdesign
  }
};
</script>
//style contribute by: Klarissa (9/13/2020)
<style scoped>
.wrapper {
  height: 100%;
  /* background-color: lightblue; */
}
.img-wrapper {
  display: flex;
  background-color: gray;
  margin: 2rem auto;
  width: 85%;
  height: 30%;
  justify-content: flex-start;
  align-items: flex-end;
}
</style>
//style contribute by: Klarissa (9/13/2020)

