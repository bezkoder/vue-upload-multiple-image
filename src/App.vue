<template>
  <div id="app">
    <div class="container" style="width:600px">
      <div style="margin: 20px">
        <h3>bezkoder.com</h3>
        <h4>Vue.js upload multiple Images</h4>
      </div>

      <upload-images></upload-images>
    </div>
  </div>
</template>

<script>
import UploadImages from "./components/UploadImages";

export default {
  name: "App",
  components: {
    UploadImages
  }
};
</script>
