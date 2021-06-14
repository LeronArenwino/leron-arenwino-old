<template>
  <div>
    <le-header></le-header>
  </div>
</template>

<script>
import LeHeader from "@/components/LeHeader";

export default {
  name: "App",
  components: { LeHeader },
};
</script>

<style>
#app {
  font-family: Roboto Condensed, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
