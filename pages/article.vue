<template>
  <div>
    <Jumbotron />
    <div class="col-xl-8 col-md-12" style="border-right:1.5px #DCDCDC solid;">
      <ArticleList />
    </div>
    <hr style="margin-right:3vw " />
  </div>
</template>
<script>
import Jumbotron from '~/components/utils/Jumbotron'
import ArticleList from '~/components/article/ArticleList'
export default {
  components: {
    Jumbotron,
    ArticleList
  }
}
</script>