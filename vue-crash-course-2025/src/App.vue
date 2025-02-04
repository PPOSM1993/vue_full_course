<script>
export default {
  data() {
    return {
      name: 'Pedro Osorio',
      status: false,
    }
  }
}
</script>

<template>
  <h1>{{name}}</h1>
  <br>
  <p v-if="status">User is activate</p>
  <p v-else="status">User is inactivate</p>
</template>

<style>

* {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
}

</style>
