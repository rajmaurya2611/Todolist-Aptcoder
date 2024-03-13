<template>
  <div>
    <div class="bg-yellow-200 text-black font-bold p-4 m-4">
      <h1 class="text-center text-lg md:text-2xl">To Do List</h1>
    </div>
    <div class="p-4">
      <router-view/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
/* You can add scoped styles here if needed */
</style>
