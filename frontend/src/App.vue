<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import LoginModalComponent from './components/LoginModalComponent.vue';
import HeroComponent from './components/HeroComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    LoginModalComponent,
    HeroComponent,
  },
}
</script>


<template>
  <HeaderComponent />
  <HeroComponent intro-text="WAKANDA FOREVER" />
  <LoginModalComponent />
  <FooterComponent />
</template>