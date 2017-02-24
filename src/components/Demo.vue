<template lang="html">
  <div class="">
    <div class="">
      {{ example }}
    </div>
    <div class="">
      {{ message }}
    </div>
  </div>
</template>

<script>
export default {
  props: ['message', 'array'],
  data(){
    return{
      example: 'This is a component'
    }
  }
}
</script>

<style lang="css">
</style>
