<script>

export default{
  name: "Header",
  
}

</script>

<template>
 
<nav>
    <div>
        <figure>
            <img src="../assets/img/dc-logo.png" alt="">
        </figure>

        
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
    </div>

</nav>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables.scss" as *;
nav{
    display: flex;
    width: 100%;
    div{
        width: $limit;
        justify-content: space-between;
        display: flex;
        align-items: center;
        margin: 0 auto;
        ul{
            display: flex;
            list-style-type: none;
            gap: 10px;
            li{
                display: flex;
                align-items: center;
                height: 104px;
                
                font-weight: bold;
                cursor: pointer;
                &:hover{
                    color: #0089FF;
                    border-bottom: 3px solid $blueDC;
                }
            }
        }
    }

}

</style>
