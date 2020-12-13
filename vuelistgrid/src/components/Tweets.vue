<template>
  <div id="tweets">Tweets</div>
</template>
<script>
export default {
  name: "vue-tweets",
  data() {
    return {
      tweets: [
        {
          author: "Karen",
          date: "December 13, 2020",
          text: "Tweet, Tweet, Tweet",
        },
        {
          author: "Karen",
          date: "December 13, 2020",
          text: "Tweeter, Tweeter, Tweeter",
        },
        {
          author: "Karen",
          date: "December 13, 2020",
          text: "Twitter, Twitter, Twitter",
        },
      ],
    };
  },
};
</script>
<style scoped>
</style>