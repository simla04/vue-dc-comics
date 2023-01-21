<template>
    <div>
        <div class="box flex">

            <section>
                <img  src="../../assets/img/dc-logo.png" alt="logo dc comics" class="logo">
            </section>
            <section>

                <ul class="flex">
                    <li class="distance">CHARACTER</li>
                    <div class="customization-blue"><li class="distance lightblue-color">COMICS</li></div>
                    <li class="distance">MOVIES</li>
                    <li class="distance">TV</li>
                    <li class="distance">GAMES</li>
                    <li class="distance">COLLECTIBLES</li>
                    <li class="distance">VIDEOS</li>
                    <li class="distance">FANS</li>
                    <li class="distance">NEWS</li>
                    <li class="distance">SHOP</li>
                </ul>

            </section>
        </div>
        
        <HeaderComp2/>
    </div>
    
</template>

<script>
    import HeaderComp2 from './HeaderComp2.vue'
    
    export default {
       name:"HeaderComp1",
       components:{
        HeaderComp2,
        
       }
       
    }
</script>

<style lang="scss" scoped>
.box{
    width:100%;
    justify-content: space-around;
    
}
.flex{
    display: flex;
}
.logo{
    width: 90%;
    padding: 10px;
}
.distance{
    margin: 0 20px;
    font-weight: bold;
    color: black;
}
.customization-blue{
    display: flex;
    align-items: center;
    height: 116px;
    border-bottom: 5px solid #0C7CEC;
    padding-top: 5px;
}
.lightblue-color{
    color: #0C7CEC;
}
li{
    display: flex;
    align-items: center;
}
</style>