<template>
  <div class="home">
    <div class="navbar">
      <TheNavbar/>
    </div>
    <div class="main">
      <Title titre="BIO"/>
    </div>
    <div class="footer"></div>
  </div>
</template>

<script>
// @ is an alias to /src
import TheNavbar from '@/components/TheNavbar'
import Title from '@/components/TitleSection'

export default {
  name: 'Home',
  components: {
    TheNavbar,
    Title
  }
}
</script>

<style lang='scss'>
@import '../scss/main.scss';

.home{
  display: grid;
  grid-template-rows: 20% 80% 20%;
}

</style>
