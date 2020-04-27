<script>
import Vue from 'vue';
import SeeOnGithub from '@/see-on-github.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    SeeOnGithub
  }
});
</script>

<template>
  <div id="app">
    <see-on-github linkTo="https://github.com/yudin-s/nuxt-ghpages-boilerplate" />
  </div>
</template>
