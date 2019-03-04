<template>
  <div class="single-post-page">
    <section class="post">
      <h1 class="post-title">POST TITLE</h1>
      <div class="post-details">
        <div class="post-detail">last updated on xxx</div>
        <div class="post-detail">written by</div>
      </div>
      <p class="post-content">content of the post</p>
      <section class="post-feedback">
        <p>letme know what you think of the post <a href="mailto:hleon57@gmail.com">Feedback suport</a></p>
      </section>
    </section>  
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
  .single-post-page {
  padding: 30px;
  text-align: center;
  box-sizing: border-box;
}

.post {
  width: 100%;
}

@media (min-width: 768px) {
  .post {
    width: 600px;
    margin: auto;
  }
}

.post-title {
  margin: 0;
}

.post-details {
  padding: 10px;
  box-sizing: border-box;
  border-bottom: 3px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

@media (min-width: 768px) {
  .post-details {
    flex-direction: row;
  }
}
</style>