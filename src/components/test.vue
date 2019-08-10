
<template>
    <div id="app">
        {{ msgs }}
    </div>
</template>
<script>
export default {
  name: 'testVue',
  props: {
    msgs: String
  }
}
</script>