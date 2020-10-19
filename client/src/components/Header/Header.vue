<template>
  <div class="header">{{ msg }}</div>
</template>

<script>

export default {
  name: 'Header',
  props: {
    msg: String
  }
}


</script>

<style scoped>

.header {
  position: absolute;
  background: #232323;
  color: #fff;
  width: 100%;
  left: 0;
  top: 0;
  height: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 28px;
}

</style>