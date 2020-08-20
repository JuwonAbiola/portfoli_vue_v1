<template>
  <div class="home">
    <First/>
    <Second/>
    <Third/>
  </div>
</template>

<script>
// @ is an alias to /src
import First from '@/components/First.vue'
import Second from '@/components/Second.vue'
import Third from '@/components/Third.vue'
export default {
  name: 'Home',
  components: {
    First,
    Second,
    Third
  }
}
</script>
