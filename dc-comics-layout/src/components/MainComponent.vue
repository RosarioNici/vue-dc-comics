<template>
    <main id="MainComponent"> 
        <section class="container-main">
            <div class="card" > 
            {{card.series}}
            <CardComponent :data="card" v-for="card in cards" :key="card.thumb"/>
            </div>
        </section>
    </main>
 
</template>

<script>
   import CardComponent from '@/components/CardComponent.vue';

export default {
name: 'MainComponent',

props:{
    cards:Array,
},
components:{
    CardComponent,
   
},

}
</script>

<style lang="scss">
$zero-auto: 0 auto;
    main{
        width: 100%;
        height: 300px;
        color: white;
        background-color: black;
        margin: $zero-auto;
    }
    .container-main{
        margin: $zero-auto;
        max-width: 1200px;
    }

</style>