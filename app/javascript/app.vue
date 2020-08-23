<template>
  <div>
    <DxSelectBox></DxSelectBox>
  </div>
</template>

<script>
  import DxSelectBox from 'devextreme-vue/select-box'
  export default {
    components: {
      DxSelectBox
    },
    data: function () {
      return {
        message: "Hello Vue!"
      }
    }
  }
</script>

<style scoped>
  p {
    font-size: 2em;
    text-align: center;
  }
</style>
