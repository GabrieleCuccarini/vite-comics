<script>

</script>

<template>
    <div class="container-fluid">
        <div class="mini-container d-flex flex-column flex-wrap">
            <ul class="list-unstyled"><h4>DC COMICS</h4>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
            </ul>
            <ul class="list-unstyled"><h4>SHOP</h4>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
            <ul class="list-unstyled"><h4>DC</h4>
                <li><a href="#">Terms of use</a></li>
                <li><a href="#">Privacy policy(New)</a></li>
                <li><a href="#">Ad choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscriptions</a></li>
                <li><a href="#">Talent Workshops</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
            <ul class="list-unstyled"><h4>SITES</h4>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
            </ul>
        </div>
        <div class="bg-image" alt=""></div>
    </div>
</template>

<style scoped lang="scss">
.bg-image {
    position: absolute;
    top: -40px;
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
