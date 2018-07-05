<template>
  <div id="app">
    <UploadFile />
  </div>
</template>

<script>
import UploadFile from './components/UploadFile.vue';

export default {
  name: 'app',
  components: {
    UploadFile,
  },
};
</script>

<style lang="scss">

body {
    font-family: 'Open-sans',Arial,Sans-serif;
    font-size:18px;
}

</style>
