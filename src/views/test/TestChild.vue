<template>
  <div>
    child
    <el-input v-model="input" placeholder="placeholder"></el-input>
    <div style="height: 2000px">child child</div>
  </div>
</template>
<script>
  export default {
    name: 'TestChild',
    data() {
      return {
        input:''
      };
    },
  };
</script>
