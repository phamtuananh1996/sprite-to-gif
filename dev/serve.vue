<script>
import Vue from 'vue';
import { SpriteToGif } from '@/entry';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    SpriteToGif,
  }
});
</script>

<template>
  <div id="app">
    <sprite-to-gif 
      image="https://images.viblo.asia/a28b8126-1298-4ca7-a507-53865b32238d.png"
      :width="100"
      :height="100"
      :column="7"
      :row="4"
      :max="27"
      :frame="20"
      :loop="10"
    />
  </div>
</template>
