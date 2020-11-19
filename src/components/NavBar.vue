<template>
  <div class="w-64 bg-blue-600">
    <div>
      <h4 class="text-white font-semibold mt-4">eCommerce</h4>
    </div>
    <div class="mt-8">
      <ul class="text-white text-left pl-4">
        <li class="p-4 bg-blue-600 rounded-3xl">
          Dashboard
        </li>
        <li class="p-4 bg-blue-600 rounded-3xl active">
          Orders
        </li>
        <li class="p-4 bg-blue-600 rounded-3xl">
          Statistics
        </li>
        <li class="p-4 bg-blue-600 rounded-3xl">
          Products
        </li>
        <li class="p-4 bg-blue-600 rounded-3xl">
          Stock
        </li>
        <li class="p-4 bg-blue-600 rounded-3xl">
          Offers
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.active {
  @apply bg-white text-black rounded-r-none;
}
</style>
