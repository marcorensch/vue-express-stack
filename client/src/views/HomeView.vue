<template>
  <div class="home">
    <Component />
  </div>
</template>

<script>
// @ is an alias to /src
import Component from '@/components/Component.vue'

export default {
  name: 'HomeView',
  components: {
    Component
  }
}
</script>
