<script>
  import NavBar from '@/components/NavBar.vue';
  import JogadorCont from '@/components/JogadorCont.vue';
  import FooterCont from '@/components/FooterCont.vue';
  export default {
    components: { NavBar, JogadorCont, FooterCont } 
  };
</script>

<template>
  <main>
    <NavBar />
    <JogadorCont />
    <FooterCont />
  </main>
</template>