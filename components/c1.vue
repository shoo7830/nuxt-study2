<template>
  <div>
    <h1>c1 컴포넌트 {{message}}</h1>
    <button @click="increment">c1 증가</button>
  </div>

</template>

<script>
  export default {
    props: {
      increment: {
        type: Function
      },

      message: {
        type: Number
      }
    },

  };
</script>

<style scoped>

</style>