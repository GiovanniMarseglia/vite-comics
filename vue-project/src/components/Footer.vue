<script>

import FooterIcon from "./FooterIcon.vue"

export default{
  name: "Footers",
  components:{
    FooterIcon
  }

}

</script>

<template>
<FooterIcon/>
<div class="containerTwo">

  <div>
    <div class="list">

      <ul>
        <span>DC COMICS</span>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Gaames</li>
        <li>Videos</li>
        <li>News</li>
          <ul>
            <span>SHOP</span>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
      </ul>
      
      <ul>
        <span>DC</span>
        <li>Terms Of Use</li>
        <li>Privacy policy (new)</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent Workshops</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
        <li>Contact Us</li>
      </ul>

      <ul>
        <span>SITES</span>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
      </ul>
    </div>

    <figure>
    
    </figure>
  </div>

</div>

<div class="ContainerThree">
  <div class="ContainerDeep">
    <button>SIGN-UP NOW</button>
    <div>
      
      <span>FOLLOW US</span>
      <i><img src="../assets/img/footer-facebook.png" alt=""></i>
      <i><img src="../assets/img/footer-twitter.png" alt=""></i>
      <i><img src="../assets/img/footer-youtube.png" alt=""></i>
      <i><img src="../assets/img/footer-pinterest.png" alt=""></i>
      <i><img src="../assets/img/footer-periscope.png" alt=""></i>
    </div>
  </div>
</div>

</template>

<style lang="scss" scoped>
@use "../styles/partials/variables.scss" as *;

.containerTwo{
  width: 100%;
  background-image: url("../assets/img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
    div{
      display: flex;
      justify-content: space-between;
      width: $limit;
      margin: 0 auto;
      .list{
      
      display: flex;
      justify-content: flex-start;
      gap: 40px;
      margin: 40px 0;
      ul{ 
        list-style-type: none;
      
        span{
          font-size: 25px;
          color: white;
          user-select: none;
          
        }
        li{
          cursor: pointer;
          line-height: 2em;
          color: grey;
          &:hover{
            color: white;
          }
        }
      }
    }
    figure{
      width: 1000px;
     
      background-position: center;
      background-repeat: no-repeat;
      background-image: url("../assets/img/dc-logo-bg.png");
    }
    }
    
}

.ContainerThree{
  width: 100%;
  background-color: #333333;
  padding: 30px 0;
  .ContainerDeep{
    width: $limit;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    button{
      padding: 10px 15px;
      color: white;
      background-color: #33333300;
      border: 2px solid $blueDC;
    }
    div{
      display: flex;
      gap: 15px;
      align-items: center;
      span{
        color: $blueDC;
        font-weight: bold;
      }
      i{
        width: 25px;
        img{
          width: 100%;
        }
      }
    }
  }
}

</style>