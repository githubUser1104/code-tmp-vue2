<template>
  <div>base</div>
</template>

<script>
export default {
  name: 'base-main',
  // 子组件
  components: {},
  // 数据绑定
  data () {
    return {
      text: 'text'
    }
  },
  // 生命周期
  created() {
    console.log(this.text);
  }
}
</script>

<style lang="scss">

</style>
