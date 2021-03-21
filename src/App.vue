<template>
<div>
  <app-header/>
  <app-featured/>
  <app-menu/>
  <app-contact/>
  <app-newsletter/>
  <app-footer/>
</div>
</template>

<script>
  import Header from './components/header-footer/Header';
  import Footer from './components/header-footer/Footer';
  import Index from './components/featured/Index';
  import Menu from './components/menu/Menu.vue';
  import Contact from './components/callUs/Contact';
  import Newsletter from './components/newsletter/Newsletter';

export default {
  components: {
    'app-header': Header,
    'app-footer': Footer,
    'app-featured' : Index,
    'app-menu' : Menu,
    'app-contact' : Contact,
    'app-newsletter' : Newsletter

  }
}

</script>

<style>
@import './assets/style.css';

</style>
