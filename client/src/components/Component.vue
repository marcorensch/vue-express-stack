<template>
  <div class="component">
    <div class="uk-section uk-section-secondary">
      <div class="uk-container">
        <div>
          <font-awesome-icon class="nx-icon" icon="user-secret" /><span>Customers</span>
        </div>
        <div>
          <font-awesome-icon class="nx-icon" icon="building" /><span>Building</span>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Component',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">

</style>
