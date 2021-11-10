<template>
<div class="home">
  <S1/>
  <S2/>
  <S3/>
</div>
</template>

<script>
import S1 from '../components/s1.vue'
import S2 from '../components/s2.vue'
import S3 from '../components/s3.vue'
export default {
  components: {
    S1,
    S2,
    S3
  },
  setup () {
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
</style>