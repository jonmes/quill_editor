<script setup>
import { ImageResize } from "quill-image-resize-module";

const modules = {
  name: "ImageResize",
  module: ImageResize,
};
</script>
<template>
  <div>
    <quill-editor theme="snow" toolbar="full" :modules="modules"></quill-editor>
  </div>
</template>

<style scoped></style>
