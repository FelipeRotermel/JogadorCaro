<script>
  import NavBar from '@/components/NavBar.vue'
  import CustoCont from '@/components/CustoCont.vue';
  import FooterCont from '@/components/FooterCont.vue';
  export default {
    components: { NavBar, CustoCont, FooterCont }
  }
</script>

<template>
  <main>
    <NavBar />
    <CustoCont />
    <FooterCont />
  </main>
</template>
