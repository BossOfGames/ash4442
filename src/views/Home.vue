<template>
  <div class="home">
    <div style="position: absolute; top: 0; z-index: -50;background: center no-repeat url('/cover.jpg'); background-size: cover; height: 100vh; width: 100vw;">
      <div style="background: #000; width: 100%; height: 100%; opacity: .55;"></div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
