<template>
  <div>
    <nuxt-link to="/">메인 페이지</nuxt-link>
    <nuxt-link to="/users/profile/1">1유저</nuxt-link>
    <nuxt-link to="/users/profile/2">2유저</nuxt-link>
    <nuxt-link to="/users/profile/잘못된유저">잘못된유저</nuxt-link>
    <nuxt />
  </div>

</template>

<script>
  export default {
    name: 'default-layout'
  };
</script>

<style scoped>

</style>