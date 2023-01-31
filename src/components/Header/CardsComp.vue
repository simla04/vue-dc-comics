<template>
    <div class="cardcont">
        <div>
            <div class="imgcard" >
                <img :src="cards.thumb" alt="comix">
            </div>
            <div>
                <h3>{{cards.series}}</h3>
            </div>
            
        </div>
        
        
    </div>
</template>

<script>
export default {
    name:"CardsComp",
    props:{
        cards: Object
    }
}
</script>

<style lang="scss" scoped>

.cardcont{
    display: flex;
    flex-direction: column;
    width: calc(100% /6 - 10px); 
    height:20%;
    justify-content: center;
    margin-top: 50px;
    
}
h3{
   padding:0 80px;
   color:white;
}

.imagcard{
    height: 300px;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;

}
.imagcard img{
        width: 50%;
        height:200px;
        object-fit:cover;
    }


</style>
