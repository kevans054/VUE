<template>
  <div class="myTeamGrid">
    <div>This is the Meet the Team section</div>
    <div>Description of team members and projects here</div>
    <div>Description of team members and projects here</div>
  </div>
</template>

<script>
export default {
  name: "vue-meet-dev",
};
</script>

<style scoped>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  display: inline-block;
}
.myTeamGrid {
  display: grid;
  position: relative;
  grid-template-columns: 100%;
  grid-template-rows: 200px 200px 200px;
  margin: 70px 0px 0;
   padding: 10px;
  background-color:rgb(194, 191, 191);
  font-size: 30px;
  text-align: left;
  max-width: 1200px;
  max-height: 600px;
}
</style>