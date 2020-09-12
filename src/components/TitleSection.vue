<template>
  <h2>
    {{titre}}
  </h2>
</template>

<script>
export default {
  name: 'Title',
  props: [
    'titre'
  ]

}
</script>

<style lang="scss" scoped>
  @import '../scss/main.scss';

  h2{
    color: $black;
    margin: 30px;
    text-align: center;
  }
</style>