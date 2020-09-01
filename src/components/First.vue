<template>
  <div>
      <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
    name: 'First',
    props: {
        msg: String,
    }
}
</script>

<style scoped>
    h1{
        color: white;
        padding: 10px 50px;
        background-color: #2abd7a;
    }
</style>