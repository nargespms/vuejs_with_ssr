<template>
  <div>
    <div class="main_news_wrapper ">
        <NewsList/>
    </div>
    <div class="sidebar">
        <wrappertab/>
        <survey/>
    </div>
  </div>
</template>

<script>
import NewsList from '../components/elements/NewsList.vue';
import wrappertab from '../components/elements/wrappertab.vue';
import survey from '../components/content/survey.vue';

export default {
 components: {
     NewsList,
     wrappertab,
     survey
 }

}
</script>

<style lang="scss">
.sidebar {
    width: 40%;
    float: right;
    box-sizing: border-box;
    padding-right: 16px;
    margin-top: 24px;
    box-sizing: border-box;
}
.main_news_wrapper {
    width: 60%;
    float: right;
    background-color: #ccccc6;
    padding: 12px;
    box-sizing: border-box;
    margin-top: 24px;
}

</style>
