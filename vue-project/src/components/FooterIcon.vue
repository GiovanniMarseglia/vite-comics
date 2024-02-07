<script>

export default{
  name: "FooterIcon",
  
}

</script>

<template>
 
<div class="container">

    <div>
        <ul>
            <li>
            <i><img src="../assets/img/buy-comics-digital-comics.png" alt=""></i>
            <p>DIGITAL COMICS</p>
            </li>


            <li>
            <i><img src="../assets/img/buy-comics-merchandise.png" alt=""></i>
            <p>DC MERCHANDISE</p>
            </li>


            <li>
            <i><img src="../assets/img/buy-comics-subscriptions.png" alt=""></i>
            <p>SUBSCRIPTION</p>
            </li>



            <li>
            <i><img src="../assets/img/buy-comics-shop-locator.png" alt=""></i>
            <p>COMIC SHOP LOCATOR</p>
            </li>



            <li>
            <i><img src="../assets/img/buy-dc-power-visa.svg" alt=""></i>
            <p>DC POWER VISA</p>
            </li>
        </ul>
    </div>

</div>


</template>

<style lang="scss" scoped>
@use "../styles/partials/variables.scss" as *;
.container{
    background-color: $blueDC;
    width: 100%;
    padding: 30px;
        div{
            width: $limit;
            margin: 0 auto;
                ul{
                    list-style-type: none;
                    display: flex;
                    justify-content: space-between;
                    li{
                        color: white;
                        display: flex;
                        align-items: center;
                        gap: 15px;
                        i{
                            display: flex;
                            
                            width: 50px;
                            img{
                                width: 100%;
                            }
                        }
                    }
                }
        }
}

</style>