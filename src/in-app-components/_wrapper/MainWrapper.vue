<template>
  <div id="wrapper">
    <navbar-view></navbar-view>
    <router-view></router-view>
    <footer-view></footer-view>
  </div>
</template>

<script>
import InAppMainNavbar from '../../in-app-components/_wrapper/MainNavbar';
import InAppMainFooter from '../../in-app-components/_wrapper/MainFooter';

export default {
  components: {
    'navbar-view': InAppMainNavbar,
    'footer-view': InAppMainFooter,
  },
  data() {
    return {
    };
  },
  ready() {
  },
};
</script>

<style lang="scss" scoped>
#wrapper {
  > .container {
    padding-top: 15px;
  }
}
</style>
