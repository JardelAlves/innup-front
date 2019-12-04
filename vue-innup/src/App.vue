<template>
  <div>
    <Toolbar/>
    <Footer/>
  </div>
</template>

<script>
import Footer from './components/Footer';
import Toolbar from './components/Toolbar';

export default {
  name: 'App',

  components: {
    Footer,
    Toolbar,
  },
};
</script>
