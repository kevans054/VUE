<template>
  <div>
    <button @click="toggleView">Toggle View</button>
    <div id="tweets" :class="{ 'list-view': listview }">
      <vue-tweets-container
        v-for="(tweet, index) in tweets"
        v-bind:key="index"
        v-bind:myAuthor="tweets.author"
        v-bimd:myDate="tweets.date"
        v-bind:myText="tweets.text"
      >
      </vue-tweets-container>
    </div>
  </div>
</template>
<script>
// import VueTweets from "./Tweet.vue";
export default {
  name: "vue-tweets-container",

  data() {
    return {
      listview: false,
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
  methods: {
    toggleView() {
      this.listview = !this.listview;
      alert('toggleview');
    },
  },
};
</script>
<style lang="scss" scoped>
.tweets {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  background-color: rgb(156, 157, 233);
  margin-top: 10px;
}
.tweets.list-view.list-view {
  grid-template-columns: 1fr;
}
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