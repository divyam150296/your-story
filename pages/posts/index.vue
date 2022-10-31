<template>
  <div class="post-page">
    <PostList />
  </div>
</template>

<script>
import PostList from '~/components/Posts/PostList'

export default {
  components: {
    PostList
  }
}
</script>


<style scoped>
.post-page {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
</style>