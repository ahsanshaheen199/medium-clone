<template>
  <div class="navbar-wrapper bg-black text-white py-4">
      <div class="container mx-auto">
        <div class="flex items-center">
            <div class="w-1/4">
                <h2>Medium Clone</h2>
            </div>
            <div class="w-3/4">
                <div class="flex justify-end items-center">
                    <router-link exact-active-class="bg-gray-500" active-class="bg-gray-500" class="px-3 py-2 rounded hover:bg-gray-500" to="/">Home</router-link>
                    <router-link  exact-active-class="bg-gray-500" active-class="bg-gray-500" class="px-3 py-2 rounded hover:bg-gray-500" to="/login">Login</router-link>
                    <router-link  exact-active-class="bg-gray-500" active-class="bg-gray-500" class="px-3 py-2 rounded hover:bg-gray-500" to="/register">Register</router-link>
                </div>
            </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>