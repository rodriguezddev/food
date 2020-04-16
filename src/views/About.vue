<template>
  <div class="about">
    <Contactanos></Contactanos>
    <Foot></Foot>
  </div>
</template>

<script>
import Contactanos from '@/components/Contactanos.vue';
import Foot from '@/components/Footer.vue';
export default {
  name:'About',
  components: {
    Contactanos, Foot
  }
}
</script>
