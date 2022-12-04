<script>

</script>

<template>
    <div class="container-fluid d-flex justify-content-around">
        <div class="left-container">
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="right-container d-flex justify-content-center align-items-center">
            <h4>FOLLOW US</h4>
            <img src="../img/footer-facebook.png" alt="">
            <img src="../img/footer-twitter.png" alt="">
            <img src="../img/footer-youtube.png" alt="">
            <img src="../img/footer-pinterest.png" alt="">
            <img src="../img/footer-periscope.png" alt="">

        </div>
    </div>
</template>

<style scoped>

button {
    background-color: rgb(48,48,48);
    border: 2px solid rgb(2,130,249)
}

.left-container {
    width: 40%;
}
.right-container {
    width: 60%;
}

.right-container > * {
    margin: 0 10px;
}
   .container-fluid {
    position: relative;
    z-index: 3;
    padding: 30px 0;
    margin-left: -32px;
    width: 100vw;   
    background-color: rgb(48,48,48);
   }

   h4 {
    color: rgb(2,130,249)
   }
</style>
