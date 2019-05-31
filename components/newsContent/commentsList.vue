<template>
    <div class="commentsList_wrapper">
        <div class="commentsList_Header">
            <span>
                users comments
            </span>
        </div>
        <ul class="commentsList">
            <li v-for="comment in comments" :key="comment.index">
                <div class="cm_inner_wrapp">
                    <h3>
                        name:  {{comment.name}}
                    </h3>
                    <time>
                        date: {{comment.date}}
                    </time>
                    <h4>
                        {{comment.content}}
                    </h4>

                </div>

            </li>
        </ul>
    </div>
</template>

<script>
  import comments from '../../data/comments.json'

  export default {
      name: 'commentsList',
      data() {
          return {
              comments : comments,
          }
      }
  }
</script>

<style>
  .commentsList_Header {
    background-color: #2ab7ae;
    border: 1px solid #2ab7ae;
    padding: 6px 8px;
    color: #fff;
    -webkit-box-shadow: inset 0 1px 2px 2px rgba(0, 0, 0, 0.35);
    -moz-box-shadow: inset 0 1px 2px 2px rgba(0, 0, 0, 0.35);
    box-shadow: inset 0 1px 2px 1px rgba(0, 0, 0, 0.35);
  }

</style>

