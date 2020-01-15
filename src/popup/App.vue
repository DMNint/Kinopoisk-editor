<template>
  <div>
    <transition name="fade">
      <Main/>
    </transition>
  </div>
</template>

<script>
import Main from './Main.vue';

export default {
  data () {
    return {}
  },  
  components: {
    Main,
  }
}
</script>