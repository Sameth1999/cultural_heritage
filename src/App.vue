<template>
  <HeaderSection/>
  <router-view></router-view>
  <FooterSection/>
</template>

<script>
import FooterSection from './components/FooterSection.vue';
import HeaderSection from './components/HeaderSection.vue';



export default {
  components: {
    HeaderSection,
    FooterSection,
  }
}
</script>