<template>

</template>

<script>
import AppHeader from "./src/components/AppHeader.vue";

export default {
  name: "App",
  components: {
  },
  mounted() {
    
    // ASCII art
    const owl = `
      /\\︵-︵/\\
      |(◉)(◉)|
      \\ ︶V︶ /
      /↺↺↺↺\\
      ↺↺↺↺↺|
      \\↺↺↺↺/
      ¯¯/\\¯¯/\\¯¯`;

    const iSeeYouText = `Thanks for visiting my site! You can find more projects in my GitHub: https://github.com/vivian-xw7`;

    console.log(owl);
    console.log(iSeeYouText);
  },
};
</script>

<style scoped>

</style>
