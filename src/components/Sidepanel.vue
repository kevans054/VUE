<template>
  <div class="myGrid">
    <div>This is the side-panel</div>
    <div>This is the side-panel</div>
    <div>This is the side-panel</div>
  </div>
</template>

<script>
export default {
  name: "vue-side-panel",
};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  display: inline-block;
}
.myGrid {
  display: grid;
  position: absolute;
  grid-template-columns: 100%;
  grid-template-rows: 200px 200px 200px;
  margin: 40px 0 0;
  padding: 10px;
  background-color: #ffc0cb;
  font-size: 30px;
  text-align: left;
  max-width: 350px;
  max-height: 600px;
}
</style>