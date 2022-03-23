<template>
  <div>
    <h1>hello, username 👋</h1>
    <h1 @click="$router.push('/posts')">👉 <span>click here</span></h1>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
span {
  text-decoration: underline;
}
</style>
