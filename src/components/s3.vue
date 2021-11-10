<template>
<section class="section-3">
  <h2 class="title">ROTATE</h2>
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
    transform: rotateX(20deg);
    text-shadow:0 .5rem #fccb90,0 1rem #d57eeb;
  }
  100%{
    transform: rotateX(-20deg);
    text-shadow: 0 -.5rem #fccb90,0 -1rem #d57eeb;
  }
}
.section-3{
  background-color: #ebedee;
  perspective: 500px;
  overflow: hidden;
  .title{
    font-size: 6rem;
    font-weight: bold;
    color: #fff;
    line-height: 80vh;
    text-shadow: .5rem 0 #fccb90, 1rem 0 #d57eeb;
    animation: rotate 4s infinite alternate ease-in-out;
  }
}
</style>