<template>
  <div class="contact">
    <Content></Content>
    <Footer></Footer>
  </div>
</template>

<script>
import content from '../components/Contact_content.vue'
import Footer from '../components/Home_footer.vue'
export default {
  components: {
    'Content': content,
    'Footer': Footer
  }
}
</script>
<style lang='less' scoped>
.contact{
  background-color: #f5f5f5;
  overflow: hidden;
}
</style>
