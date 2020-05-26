<template>
  <TestComp/>
  <TestCompWithH/>
</template>

<script>
import TestComp from './TestComp.vue'
import TestCompWithH from './TestCompWithH.vue'

export default {
  name: 'App',
  components: {
    TestComp,
    TestCompWithH
  }
}
</script>
