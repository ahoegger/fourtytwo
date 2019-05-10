<template>
  <div class="about">
    <h1>This is an about page</h1>
   <!-- <chartjs-bar></chartjs-bar> -->
   <RandomChart></RandomChart>
  </div>
</template>
<script>
import RandomChart from '@/components/RandomChart.vue'
  // import { Bar } from 'vue-chartjs'
  export default {
    components: {
      RandomChart
    }
  
  }
</script>
