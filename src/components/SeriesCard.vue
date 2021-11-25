<template>
  <div class="series-card">
    <img :src="serie.thumb" alt="serie.series">
    <h4>{{serie.series}}</h4>
  </div>
</template>

<script>
export default {
  name:'SeriesCard',
  props:{
    serie: Object
  }
}
</script>

<style lang="scss" scoped>
  .series-card{
    width: calc(100% / 6);
    height: 260px;
    padding: 10px;
    margin-bottom: 30px;
      img {
        width: 100%;
        height: calc(100% - 20px);
        object-fit: cover;
        object-position:top;
      }
      h4 {
        padding-top: 15px;
        color: white;
        text-transform: uppercase;
      }
  }
</style>
