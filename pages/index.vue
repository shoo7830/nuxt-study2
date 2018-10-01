<template>
  <div>
    <c1 :message="n" :increment="increment"></c1>
    <h1>index 페이지 {{n}}</h1>
    <button @click="increment">index 증가</button>
  </div>

</template>

<script>
  import c1 from '../components/c1.vue'
  //import c2 from '../components/c2.vue'
  export default {
    name: 'page-index',
    components: {c1},
    data() {
      return {
        n:1
      }
    },

    methods: {
      increment() {
        this.n += 1
      }
    }
  };
</script>

<style scoped>

</style>

