<template>
  <div class="about">
    <div class="word">
      <div><img src="../assets/About/03_About_03.png" alt="wordImg"></div>
      <div class="container"><span>I am a Graphic & Web Designer based in New York, specializing in User Interface Design and Development </span></div>
    </div>
    <Content></Content>
    <Footer></Footer>
  </div>
</template>

<script>
import content from '../components/About_content.vue'
import Footer from '../components/Home_footer.vue'
export default {
  components: {
    'Content': content,
    'Footer': Footer
  }
}
</script>

<style lang="less" scoped>
.about{
  text-align: center;
  overflow: hidden;
  width: 100%;
}
.word{
  background-color: #3e3e3e;
  height: 300px;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center
}
.container{
  width: 100%;
  display: flex;
  justify-content: center;
}
span{
  display: block;
  line-height: 32px;
  overflow-wrap: break-word;
  width: 500px;
  margin-top: 40px;
  color: #b6b6b6;
  white-space: pre-wrap;
}

</style>
