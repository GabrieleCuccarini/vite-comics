<script>
import { toValidAssetId } from '@vue/compiler-core';

export default {
     data() {
       return {
            navlinks: [
            { title: "CHARACTERS",
              url: "/"
            } ,{ title: "COMICS",
              url: "/"
            }, { title: "MOVIES",
              url: "/"
            }, { title: "TV",
              url: "/"
            }, { title: "GAMES",
              url: "/"
            }, { title: "VIDEOS",
              url: "/"
            }, { title: "FANS",
              url: "/"
            }, { title: "NEWS",
              url: "/"
            }, { title: "SHOP",
              url: "/"
            }
          ]
     }
  }
}
</script>

<template>
  <div class="container-fluid d-flex justify-content-around align-items-center">
    <div class="left-side d-flex flex-shrink-0">
      <img src="../img/dc-logo.png" alt="">
    </div>
    <div class="right-side">
      <ul class="d-flex list-unstyled">
        <li v-for="(titolo, i) in navlinks" :key="('card_' + i)"><a :href=titolo.url>{{titolo.title}}</a></li>
      </ul>
    </div>
  </div>
</template>

<style scoped lang="scss">

.container-fluid {
  padding: 10px 0px;
  margin-left: -32px;
  margin-top: -32px;
  width: 100vw;
  }
.left-side img {
  width: 60px;
  height: 60px
}

li {
  font-size: 12px;
  padding: 10px 15px;
  a {  
    color: rgb(70,70,70);
    text-decoration: none;
  }
  &:hover {
    color: rgb(2,130,249);
    border-bottom: 2px solid rgb(2,130,249);
  }
}
</style>
