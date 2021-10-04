<template>
 <h1>I am page Meetup Detail !!!</h1>
</template>
<script>
export default {
 created(){
   debugger
   const meetupId = this.$route.params.id
 }
}
</script>
<style scoped>
h1 {
  margin-left: 30px;
}
</style>