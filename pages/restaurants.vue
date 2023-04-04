<template>
  <main class="container-restaurant">
    <h1>Restaurants</h1>
    <AppRestaurantInfo />
  </main>
</template>

<script>
import AppRestaurantInfo from "../components/AppRestaurantInfo.vue"
export default {

    name: 'restaurantPage',
    components: {
        AppRestaurantInfo
    }
}
</script>

<style>

</style>