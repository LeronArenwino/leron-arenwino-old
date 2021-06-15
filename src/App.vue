<template>
  <div>
    <le-header></le-header>
    <le-about-me></le-about-me>
  </div>
</template>

<script>
import LeHeader from "@/components/LeHeader";
import LeAboutMe from "@/components/LeAboutMe";

export default {
  name: "App",
  components: { LeHeader, LeAboutMe },
};
</script>

<style>
#app {
  font-family: Roboto Condensed, sans-serif;
  text-align: center;
  color: #2c3e50;
}
</style>
