<template>
  <div class="content">
    <el-row :gutter="0">
         <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="word">
             <div><img src="../assets/contact/05_Contact_03.png" alt="word" class="one"></div>
             <div><img src="../assets/contact/05_Contact_06.png" alt="word" class="two"></div>
             <div><img src="../assets/contact/05_Contact_09.png" alt="word" class="three"></div>
         </el-col>
         <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="input">
             <div class="fir">
                 <el-input  value="Your Name" class="name"></el-input>
                 <el-input  value="Your Email" class="email"></el-input>
             </div>
             <el-input  value="Your Title" class="el"></el-input>
             <el-input type="textarea" :autosize="{minRows:7}" value="Your Comment" class="el"></el-input>
             <el-button class="btn">SEND MESSAGE</el-button>
         </el-col>
    </el-row>
    <el-row :gutter="0" class="map">
        <el-col :xs="24" :sm="24" :md="24" :lg="24" :xl="24" class="img">
            <img src="../assets/contact/map.png" alt="img">
        </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
}

</script>
<style lang='less' scoped>
.word{
    display: flex;
    flex-direction: column;
    text-align: left;
    padding: 100px;
}
.one{
    width: 40%;
    height: auto;
}
.two{
    width: 83%;
    height: auto;
    margin-top: 40px;
}
.three{
    width: 75%;
    height: auto;
    margin-top: 40px;
}
.img>img{
    width: 85%;
    height: auto;
}
// input
.input{
    display: flex;
    flex-direction: column;
    padding: 100px 100px 100px 10px;
}
.fir{
    // width: 80%;
    display: flex;
    flex-direction: row;
}
.name{
    flex-basis: 270px;
}
.email{
    flex-basis: 270px;
    margin-left: 40px;
}
.el{
    padding-top: 30px;
}
.el-input__inner{
    width: 580px !important;
}
.el-textarea__inner{
    width: 580px !important;
}
.btn{
    background-color: #10c9c3;
    color: #ffffff;
    width: 200px;
    margin-top: 30px;
}
.map{
    margin-bottom: 100px;
}
</style>
