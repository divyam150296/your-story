<template>
  <section class="post-list">
    <PostPreview id="1" title="Title1" content="Preview Our Text" thumbnail="https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" />
    <PostPreview id="2" title="Title2" content="Preview Our Text" thumbnail="https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80"/>
    <PostPreview id="3" title="Title3" content="Preview Our Text" thumbnail="https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80" />
  </section>
</template>

<script>
import PostPreview from '~/components/Posts/PostPreview'

export default {
  components: {
    PostPreview
  }
}
</script>


<style scoped>
.post-list {
  display: flex;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
</style>