<script>
export default {
     data() {
       return {
            bannerlinks: [
            { title: "DIGITAL COMICS",
              img: "../public/buy-comics-merchandise.png"
            }, { title: "DC MERCHANDISE",
              img: "../public/buy-comics-merchandise.png"
            }, { title: "SUBSCRIPTION",
              img: "../public/buy-comics-subscriptions.png"
            }, { title: "COMIC SHOP LOCATOR",
              img: "../public/buy-comics-shop-locator.png"
            }, { title: "DC POWER VISA",
              img: "../public/buy-dc-power-visa.svg"
            }
          ]
     }
  }
}
</script>

<template>
    <div class="container-fluid">
        <div class="container d-flex justify-content-center">
            <div v-for="(card, i) in bannerlinks" key="(card_ + i)" class="mini-card d-flex align-items-center">
                <div class="card-img-container">
                    <img :src="card.img" alt="">
                </div>
                <a href="#">{{card.title}}</a>
            </div>
        </div>
    </div>
</template>

<style scoped>
.card-img-container img {
    margin-right: 10px;
    width: 40px;
    aspect-ratio: 1 / 1;
}

.mini-card {
    flex-basis: 20%;
}
.container-fluid {
    position: relative;
    z-index: 3;
    padding: 30px 0;
    background-color: rgb(2,130,249);
    margin-left: -32px;
    width: 100vw;
}    

a {
    margin: 0 10px;
    text-decoration: none;
    color: white;
}
</style>
