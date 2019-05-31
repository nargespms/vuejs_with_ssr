<template>
    <div class="main_news_content ">
        <newsInfo/>
        <news/>
        <sendComment/>
        <commentsList/>
    </div>
</template>

<script>
  import newsInfo from '../components/newsContent/newsInfo.vue';
  import news from '../components/newsContent/news.vue';
  import sendComment from '../components/newsContent/sendComment.vue';
  import commentsList from '../components/newsContent/commentsList.vue';

  export default {
      name: 'mainNewsContent',
      components: {
          newsInfo,
          news,
          sendComment,
          commentsList,
      }
  }
</script>

<style  scoped>
.main_news_content {
  width: 50%;
  margin: auto;
}
</style>


