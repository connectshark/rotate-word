<template>
<section class="section-2">
  <h2 class="title">5000</h2>
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
    transform: rotateY(-20deg);
    text-shadow: .5rem 0 #ffecd2, 1rem 0 #fcb69f;
  }
  100%{
    transform: rotateY(20deg);
    text-shadow: -.5rem 0 #ffecd2, -1rem 0 #fcb69f;
  }
}
.section-2{
  background-color: #1F2937;
  perspective: 500px;
  overflow: hidden;
  .title{
    font-size: 6rem;
    font-weight: bold;
    color: #fff;
    line-height: 80vh;
    text-shadow: .5rem 0 #ffecd2, 1rem 0 #fcb69f;
    animation: rotate 4s infinite alternate ease-in-out;
  }
}
</style>