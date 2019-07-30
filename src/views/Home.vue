<template>
  <div class="home">
    <div class="word">
      <div class="logo"><img src="../assets/HOME/02_Home_13.png" alt="wordImg"></div>
      <span>I am a Graphic & Web Designer based in New York, specializing  </span>
    </div>
    <home></home>
    <footerC></footerC>
  </div>
</template>

<script>
import home from '../components/Home_content.vue'
import footerC from '../components/Home_footer.vue'
export default {
  components: {
    'home': home,
    'footerC': footerC
  }
}
</script>

<style lang="less" scoped>
  .home{
    overflow: hidden;
    background-color: #f6f6f6;
    width: 100%;
  }
  .word{
    width: 100%;
    height: 300px;
    display: flex;
    justify-content: center;
    flex-direction: column;
  }
  .logo{
    width: 100%;
  }
  .logo>img{
    width: 36%;
    height: auto;
  }
  .word>span{
    color: #9f9f9f;
    margin-top: 20px;
  }
</style>
