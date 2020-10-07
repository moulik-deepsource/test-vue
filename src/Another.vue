<template>
  <!-- ✓ GOOD -->
  <div foo="bar"/>
  <div :foo="bar"/>

  <!-- ✗ BAD -->
  <div v-bind:foo="'bar'"/>
  <div :foo="'bar'"/>
</template>
<script>
<script>
Vue.component('some-comp', {
  data: {
    foo: 'bar'
  }
})

export default {
  data: {
    foo: 'bar'
  }
}
</script>
