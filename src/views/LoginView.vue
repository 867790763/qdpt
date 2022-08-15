<template>
<div class="loginbox">
  <div class="pic"></div>
  <div class="rightbox"></div>
</div>
</template>

<script>
export default {

}
</script>

<style>
.loginbox{
  background-image: linear-gradient(to right, #ba5370, #f4e2d8);

  /*严格来说background-image要做浏览器兼容*/

  display: flex; /*将整个body定义为一个flex容器*/

  justify-content: center; /*将flex项目在容器中心对齐*/
}
.pic{
  background-image: url(/src/assets/bgm.jpg);
}
</style>