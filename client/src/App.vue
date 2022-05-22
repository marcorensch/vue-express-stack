<template>
  <nav>
    <router-link to="/">Home</router-link>
    |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view/>
</template>

<script>
import UIkit from 'uikit';
import Icons from 'uikit/dist/js/uikit-icons';

UIkit.use(Icons);

export default {
  name: 'App'
};

</script>

<style lang="less">
@import "../node_modules/uikit/src/less/uikit.less";
.nx-icon{
  padding-right: 5px;
}
</style>
