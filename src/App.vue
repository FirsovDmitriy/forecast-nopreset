<template>

  <TheHeader />

  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>

  </header> -->

  <RouterView />
</template>

<script>
import TheHeader from '@/components/TheHeader.vue';

export default {
    name: "App",
    components: { TheHeader }
}
</script>

<style>

</style>
