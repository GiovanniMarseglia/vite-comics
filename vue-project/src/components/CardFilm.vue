<script>
export default {
    name:"CardFilm",
    props:{
        propsThumb:String, 
        propsName:String,
    }    
}
</script>



<template>

        <div>
        <figure>
            <img :src= propsThumb>
        </figure>
            <span>{{propsName}}</span>
        </div>
    
</template>

<style scoped lang="scss">

div{
    display: flex;
    flex-direction: column;
    width: calc( 100% / 6 - 20px);
    gap: 10px;
    figure{ 
        img{
            width: 100%;
            aspect-ratio: 1;
        }
    }
    span{
        color: white;
    }
}

</style>