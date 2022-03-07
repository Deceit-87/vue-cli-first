<template>
<div class="container">
<h1>IL MIO PRIMO JUMBO</h1>
</div>
</template>

<script>
export default {
  name: 'JumboTron',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.container{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 100px auto;
    width: 100vh;
    height: 500px;
    background-image: url('../assets/sub-category-1-1.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
</style>
