<template>
  <div class="container text-center">
    <div class="content-wrapper">
    <div class="mt-30 jumbotron jumbotron-fluid error-box">
      <div class="container">
        <h1 class="display-4">{{ title }}</h1>
        <p class="lead">{{ msg }}</p>
      </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      'title': '无法访问！',
      'msg': '糟糕，你访问的页面还在完善当中！' 
    }
  },
};
</script>

<style scoped>
.jumbotron{
  border-radius: 7px;
}
.mt-30{
  margin-top: 30px;
}
.content-wrapper{
  height: 670px;
}
</style>