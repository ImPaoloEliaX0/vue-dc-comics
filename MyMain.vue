<template>

    <main>
        
            <div class="debug">
                <h1 class="debug-text">&#10509; Content goes here &#10508;</h1>
            </div>

            <div class="icons-blue">
                <div class="icon-container">
                    <div class="single-icon-blue">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <span>DIGITAL COMICS</span>
                </div>

                <div class="single-icon-blue">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <span>DC MERCHANDISE</span>
                </div>

                <div class="single-icon-blue">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <span>SUBSCRIPTION</span>
                </div>

                <div class="single-icon-blue">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <span>COMIC SHOP LOCATOR</span>
                </div>

                <div class="single-icon-blue">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <span>DC POWER VISA</span>
                </div>

                </div>
            </div>
       
    </main>

</template>

<script>
export default {
  name: 'MyMain',
  
}
</script>


<style scoped lang="scss">

@import "../assets/style/variables.scss";
main {
    .debug {
      display: flex;
      align-items: center;
      background-color: $mainBg;
      .debug-text {
        color: $light;
        width: 80%;
        max-width: 1200px;
        margin: $verticalSpace auto;
      }
    }
    .icons-blue {
        background-color: $primaryColor;
        display: flex;
        justify-content: space-between;
        align-items: center;
    .icon-container {
        display: flex;
        width: 80%;
        max-width: 1200px;
        margin: auto;
        .single-icon-blue{
            display: flex;
            align-items: center;
            margin: $verticalSpace auto;
            img {
                height: 40px;
            }
            span {
                color: $light;
                margin-left: 10px;
                font-size: 14px;
            }
        }
    }
        
    }
}
</style>