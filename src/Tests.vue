<template>
  <div
    is="header"
    v-for="item in items"
    v-if="!visible"
    v-once
    id="uniqueID"
    ref="header"
    v-model="headerData"
    my-prop="prop"
    @click="functionCall"
    v-text="textContent">
  </div>
  <div
    v-for="item in items"
    v-if="!visible"
    prop-one="prop"
    :prop-two="prop"
    prop-three="prop"
    @click="functionCall"
    v-text="textContent">
  </div>
  <div
    prop-one="prop"
    :prop-two="prop"
    prop-three="prop">
  </div>
</template>

<script>
/* ✗ BAD */
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  props: {
    propA: Number
  }
}
</script>

