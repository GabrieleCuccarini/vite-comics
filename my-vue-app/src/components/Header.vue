<script>
export default {
     data() {
       return {
            title: "La mia prima app con Vite"
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
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
      </ul>
    </div>
  </div>
</template>

<style scoped>

.container-fluid {
  padding: 20px 0px;
  border-top: 30px solid black;
  margin-left: -32px;
  margin-top: -32px;
  width: 100vw;
  }
.left-side img {
  width: 100px;
  height: 100px
}

li {
  font-size: 12px;
  padding: 10px 15px;
}

a {  
  color: rgb(70,70,70);
  text-decoration: none;
}

a:hover {
  color: rgb(2,130,249);
  border-bottom: 2px solid rgb(2,130,249);
}
</style>
