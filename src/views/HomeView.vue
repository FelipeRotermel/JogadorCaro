<script>
  import NavBar from '@/components/NavBar.vue'
  import ContHome from '@/components/ContHome.vue'
  import FooterCont from '@/components/FooterCont.vue';
  export default {
    components: { NavBar, ContHome, FooterCont }
  }
</script>

<template>
  <main>
    <NavBar />
    <ContHome />
    <FooterCont />
  </main>
</template>
