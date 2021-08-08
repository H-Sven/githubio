<template>
  <div>
    <div @click="toast()">这是verpress中的vue组件， click me！</div>
  </div>
</template>
   
<script>
   
export default {
  name: '',
  data() {
    return {}
  },
  created() {},
  methods: {
    toast() {
      alert('hello world')
    }
  }
}
</script>
<style lang='scss'>
 
</style>