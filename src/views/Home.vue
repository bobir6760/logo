<template>
  <div class="home">
    <Navbar />
    <Ceo />
    <Servic />
    <Best />
    <Logo />
    <Finish />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import Ceo from "@/components/Ceo.vue";
import Servic from "@/components/Servic.vue";
import Best from "@/components/Best.vue";
import Logo from "@/components/Logo.vue";
import Finish from "@/components/Finish .vue";

export default {
  name: "Home",
  components: {
    Navbar,
    Ceo,
    Servic,
    Best,
    Logo,
    Finish,
  },
};
</script>
