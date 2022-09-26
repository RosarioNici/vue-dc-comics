<template>
  <div class="cards-container">
    <div >
       sono una card
    </div>
  </div>
</template>

<script>

export default {
    name: 'CardComponent',
props:{
    data: Object,
}
}
</script>

<style>
    .cards-container{
        display: flex;
        align-items: center;
        flex-wrap: wrap;
        max-width: 1200px;
        margin: 0 auto;
    }
.card{
    color: white;
    width: calc(100% / 4);
    height: 150px;

}
</style>