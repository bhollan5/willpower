<template>
  <div id="dash">
    <h1>This is an about page</h1>
    <contributionCalendar :history="history" :year="2016" :cellClick="someMethod" />
  </div>
</template>

<script>
import contributionCalendar from 'vue-contribution-calendar';

export default {
  data() {
    return {
      history: {
        '20-12-2018': 7,
        '18-1-2019': 1 
      }
    }
  },
  methods: {
    someMethod() {

    }
  },
  components: {
    contributionCalendar
  }
}
</script>

<style scoped lang="scss">
@import '@/globalVars.scss';

</style>
