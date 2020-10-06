<template>
  {{ 'Lorem ipsum' }}
  {{ "Lorem ipsum" }}
  {{ `Lorem ipsum` }}
</template>
<script>
Vue.component('some-comp', {
  data: function() {
return {
    foo: 'bar'
  };
}
})
export default {
  data: function() {
return {
    foo: 'bar'
  };
}
}
</script>
