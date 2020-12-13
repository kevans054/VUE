<template>
  <div>
      <article class="tweets">
        <vue-tweets>
        <h4>{{ tweets.myAuthor }}</h4>
        <h6>{{ tweets.myDate }}</h6>
        <p>{{ tweets.myText }}</p>
        </vue-tweets>
      </article>
  </div>
</template>
<script>
import VueTweetsContainer from "./TweetsContainer.vue"
export default {
  name: "vue-tweets",
  props: 
    ['myAuthor',
    'myDate',
    'myText']
}
</script>
<style lang="scss" scoped>
.tweets {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  background-color: rgb(156, 157, 233);
  margin-top: 10px;
}
// .tweets.list-view {
//   grid-template-columns: 1fr;
// }
h4 {
  background-color: plum;
  font-size: 30px;
}
h6 {
  background: green;
  font-size: 30px;
}
p {
  font-size: 30px;
}
</style>