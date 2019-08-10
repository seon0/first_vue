
<template>
    <div id="app">
      <testVue msgs="안녕하세요 Vue!!"/>
    </div>
</template>
<script>
import testVue from '../components/test.vue'

export default {
  name: 'app',
  components: {
    testVue
  }
}
</script>