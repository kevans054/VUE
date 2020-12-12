<template>
  <div class="myOtherGrid">
    <div>This is the Meet the Developer section</div>
    <div>This is the Meet the Developer section</div>
    <div>This is the Meet the Developer section</div>
  </div>
</template>

<script>
export default {
  name: "vue-meet-team",
};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  display: inline-block;
}
.myOtherGrid {
  display: grid;
  position: relative;
  grid-template-columns: 100%;
  grid-template-rows: 200px 200px 200px;
  margin: 70px 400px 0;
   padding: 10px;
  background-color:rgb(194, 191, 191);
  font-size: 30px;
  text-align: left;
  max-width: 500px;
  max-height: 600px;
}
</style>