<template>
  <div><appHeader></appHeader> <ninjas></ninjas> <appFooter></appFooter></div>
</template>

<script>
import AppHeader from "./components/Header";
import AppFooter from "./components/Footer";
import Ninjas from "./components/Ninjas";

export default {
  name: "App",
  components: {
    AppHeader,
    AppFooter,
    Ninjas
  }
};
</script>

<style scoped></style>
