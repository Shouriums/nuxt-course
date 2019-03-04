<template>
  <div>
    <section class="posts-list">
      <PostPreview 
        id="1"
        title="Title 1"
        previewText="First Post"
        thumbnail="https://static.techspot.com/images2/news/bigimage/2018/07/2018-07-10-image-35.jpg"/>
      <PostPreview 
        id="2"
        title="Title 2"
        previewText="Second Post"
        thumbnail="https://static.techspot.com/images2/news/bigimage/2018/07/2018-07-10-image-35.jpg"/>
      <PostPreview 
        id="3"
        title="Title 3"
        previewText="Third Post"
        thumbnail="https://static.techspot.com/images2/news/bigimage/2018/07/2018-07-10-image-35.jpg"/>
    </section>
  </div>
</template>

<script>
  import PostPreview from '@/components/Posts/PostPreview';
  export default {
    components: {
      PostPreview
    }
  }
</script>

<style scoped>
  .posts-list {
    display: flex;
    padding: 20px;
    box-sizing: border-box;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }
</style>