<script>
export default {
     data() {
       return {
            mainlinks1: [
            { title: "Characters",
              url: "/"
            } ,{ title: "Comics",
              url: "/"
            }, { title: "Movies",
              url: "/"
            }, { title: "TV",
              url: "/"
            }, { title: "Games",
              url: "/"
            }, { title: "Videos",
              url: "/"
            }
        ],
            mainlinks2: [
            { title: "Shop DC",
              url: "/"
            } ,{ title: "Shop DC Collectibles",
              url: "/"
            }
        ], 
            mainlinks3: [
            { title: "Terms of use",
              url: "/"
            } ,{ title: "Privacy Policy(New)",
              url: "/"
            }, { title: "Ad choices",
              url: "/"
            }, { title: "Advertising",
              url: "/"
            }, { title: "Jobs",
              url: "/"
            }, { title: "Subscriptions",
              url: "/"
            }, { title: "Talent Workshops",
              url: "/"
            }, { title: "CPSC Certificates",
              url: "/"
            }, { title: "Ratings",
              url: "/"
            }, { title: "Shop Help",
              url: "/"
            }, { title: "Contact Us",
              url: "/"
            }
        ],  
            mainlinks4: [
            { title: "DC",
              url: "/"
            } ,{ title: "MAD Magazine",
              url: "/"
            }, { title: "DC Kids",
              url: "/"
            }, { title: "DC Universe",
              url: "/"
            }, { title: "DC Power Visa",
              url: "/"
            }
        ]
     }
  }
}
</script>

<template>
    <div class="container-fluid">
        <div class="mini-container d-flex flex-column flex-wrap">
            <ul class="list-unstyled"><h4>DC COMICS</h4>
                <li v-for="litem in mainlinks1">
                    <a :href=litem.url>{{litem.title}}</a>
                </li>
            </ul>
            <ul class="list-unstyled"><h4>SHOP</h4>
                <li v-for="litem in mainlinks2">
                    <a :href=litem.url>{{litem.title}}</a>
                </li>
            </ul>
            <ul class="list-unstyled"><h4>DC</h4>
                <li v-for="litem in mainlinks3">
                    <a :href=litem.url>{{litem.title}}</a>
                </li>
            </ul>
            <ul class="list-unstyled"><h4>SITES</h4>
                <li v-for="litem in mainlinks4">
                    <a :href=litem.url>{{litem.title}}</a>
                </li>
            </ul>
        </div>
        <div class="bg-image" alt=""></div>
    </div>
</template>

<style scoped lang="scss">
.bg-image {
    position: absolute;
    top: -30px;
    right: 150px;
    width: 430px;
    aspect-ratio: 1 / 1;
    background-size: contain;
    background-image: url(/src/img/dc-logo-bg.png);
}
.container-fluid {
    position: relative;
    padding: 30px 0;
    margin-left: -32px;
    width: 100vw;
    background-image: url(../img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    img {
        position: absolute;
        top: -50px;
        width: 450px;
        aspect-ratio: 1 / 1;
    }
}    
.mini-container {
    height: 300px;
    margin-left: 100px;
    width: 400px;
    color: white;
}

li {
    font-size: 12px;
    a {
        text-decoration: none;
        color:grey
    }
}
</style>
