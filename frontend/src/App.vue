<script>
import NavBar from './components/NavBar.vue';
import LoginForm from './components/LoginForm.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    LoginForm
  },
}
</script>


<template>
  <NavBar />
  <LoginForm />
</template>