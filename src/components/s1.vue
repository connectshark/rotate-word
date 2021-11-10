<template>
<section class="section-1">
  <h2 class="title">旋轉</h2>
</section>
</template>

<script>
export default {
  setup () {
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
@keyframes rotate {
  0%{
    text-shadow: .5rem 0 #199ADF, 1rem 0 #043C75;
  }
  100%{
    text-shadow: -.5rem 0 #199ADF, -1rem 0 #043C75;
  }
}
.section-1{
  background-color: #FFCC06;
  .title{
    font-size: 6rem;
    font-weight: bold;
    color: #fff;
    line-height: 80vh;
    text-shadow: .5rem 0 #199ADF, 1rem 0 #043C75;
    animation: rotate 4s infinite alternate ease-in-out;
  }
}
</style>