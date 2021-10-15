<template>
<div id="main-banner" class="main-banner">
    <h1>Make Your Burger </h1>
</div>

</template>
<script>
export default{
    name:'Banner'
}
</script>

<style scoped>
#main-banner {
    background-image: url('/img/Burger.jpg');
    background-position: 0 -250px;
    background-size: cover;
    height:600px;
    display: flex;
    align: center;
    align-items: center;
}
#main-banner h1{
    color: #FFF;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 10px 40px;
    height:90px;
    align: center;
}
</style>