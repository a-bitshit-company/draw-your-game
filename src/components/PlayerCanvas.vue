<template>
  <vue-drawing-canvas ref="VueCanvasDrawing" />
</template>

<script>
  import VueDrawingCanvas from "vue-drawing-canvas";

  export default {
    name: "PlayerCanvas",
    components: {
      VueDrawingCanvas,
    },
  };
</script>