<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
import LoginModalComponent from './components/LoginModalComponent.vue';
import HeroComponent from './components/HeroComponent.vue';
import RegisterModalComponent from './components/RegisterModalComponent.vue';

export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    LoginModalComponent,
    HeroComponent,
    RegisterModalComponent
  },
}
</script>


<template>
  <HeaderComponent />
  <HeroComponent intro-text="WAKANDA FOREVER" />
  <LoginModalComponent />
  <RegisterModalComponent />
  <FooterComponent />
</template>