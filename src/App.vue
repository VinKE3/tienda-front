<template>
  <div id="app">
    <Header />
    <router-view />
    <Footer />
  </div>
</template>

<script>
export default {
  components: {
    Header: () => import("./components/Header.vue"),
    Footer: () => import("./components/Footer.vue"),
  },
};
</script>
