<template>
    <main> <section class="container-main">
<div> <h1>--> content Goes Here >-- </h1> </div>
  </section></main>
 
</template>

<script>
export default {
name: 'MainComponent'
}
</script>

<style lang="scss">
$zero-auto: 0 auto;
    main{
        width: 100%;
        height: 30%;
        color: white;
        background-color: black;
        margin: $zero-auto;
    }
    .container-main{
        margin: $zero-auto;
        max-width: 1200px;
    }

</style>