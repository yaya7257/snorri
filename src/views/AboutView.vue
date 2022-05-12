<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
  <BootCard></BootCard>
</template>

<script>
import BootCard from '@/components/BSCard.vue'

export default {
  name: 'AboutView',
  components: {
    BootCard
  }
}
</script>
