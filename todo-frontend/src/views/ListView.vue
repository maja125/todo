<template>
  <!-- views folder sluzi da se objedini nekoliko komponenti u celoviti prikaz -->
  <div>
    <!--3. Renderujemo komponentu -->
    <span>TEST 123</span>
    <Navbar />
    <List />
  </div>
</template>

<script>

import Navbar from "@/components/Navbar.vue";
import List from "@/components/List.vue";
export default {
  // 2. registrujemo komponentu
  components: {
    Navbar,
    List
  }
};
</script>

<style scoped>
</style>
