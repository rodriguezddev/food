<template>
  <div class="home">
    <Game></Game>
    <Foot></Foot>
  </div>
</template>

<script>
// @ is an alias to /src
import Game from '@/components/Game.vue'
import Foot from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Game, Foot
  }
}
</script>
