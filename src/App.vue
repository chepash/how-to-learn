<template>
  <MainPage v-if="windowWidth >= 1100" />
  <PlaceHolder v-else />
</template>

<script>
import MainPage from "./components/MainPage.vue";
import PlaceHolder from "./components/PlaceHolder/PlaceHolder.vue";

export default {
  name: "App",
  components: {
    MainPage,
    PlaceHolder,
  },
  data() {
    return {
      windowWidth: window.innerWidth,
    };
  },
  created() {
    window.addEventListener("resize", this.handleResize);
  },
  unmounted() {
    window.removeEventListener("resize", this.handleResize);
  },
  methods: {
    handleResize() {
      this.windowWidth = window.innerWidth;
    },
  },
};
</script>
