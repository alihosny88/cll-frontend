<template>
  <div>
    <div class="container wrapper">
      <div class="w-full px-4 flex justify-between items-center mb-6">
        <!-- Left Logo -->
        <div class="logos-dimintions">
          <img
            src="../public/logo2.jpeg"
            alt="Left Logo"
            class="h-15"
          />
        </div>

        <!-- Right Logo -->
        <div class="logos-dimintions">
          <img
            src="../public/logo1.jpeg"
            alt="Right Logo"
            class="h-15"
          />
        </div>
      </div>
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
@media (min-width: 1536px) {
  .container {
    max-width: 1316px !important;
  }
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
.logos-dimintions {
  margin-top: 5%;
}
.wrapper {
  margin: auto;
}
</style>
