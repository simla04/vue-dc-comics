<template>
    <div class="background">
        <h2>CURRENT SERIES</h2>
    </div>
</template>

<script>
    export default {
        name:"BackgImage",
    }
</script>

<style lang="scss" scoped>
.background{
    background-image: url(../../assets/img/jumbotron.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    width: 100%;
    
    
}
h2{
    position: relative;
    background-color: #0C7CEC;
    width: 15%;
    padding:15px;
    top: 470px;
    left:80px;
    font-size: 2rem;
    text-align: center;
}
</style>