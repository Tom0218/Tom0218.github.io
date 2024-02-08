<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>

  <!-- <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
      </nav>
    </div>
  </header> -->
  <body>
    <RouterView />
  </body>
</template>

<style lang="scss" scoped>
body{
  height: auto;
  width: 100vh;
}

</style>
