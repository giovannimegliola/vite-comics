<template>
  <footer>
    <section class="footer_top">
        <div class="container my-auto">
            <div class="row ">
                <div class="col-auto padding-top">

                    <span>DC COMICS</span>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>

                    <span>SHOP</span>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>


                </div>
                <div class="col-auto padding-top">

                    <span>DC</span>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscription</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
                <div class="col-auto padding-top">

                    <span>SITES</span>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>

                </div>

                <div class="col-5 logodc">
                    <img src="../assets/img/dc-logo-bg.png" alt="" class="logo DC">
                </div>
            </div>
        </div>
    </section>
    <section class="footer_bottom">
        <div class="container">
            <div class="row">
                <div class="col">
                    <div class="btn">SING-UP NOW!</div>
                </div>
                <div class="col">
                    <ul class="justify-content-end">
                        <li class="social" >FOLLOW US</li>
                        <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a></li>
                        <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a></li>
                    </ul>
                </div>
            </div>
        </div>    
    </section>
  </footer>
</template>

<script>
  export default {
    name: 'FooterApp'
    
  }
</script>

<style lang="css" scoped>
.footer_top{
  background-image: url('../assets/img/footer-bg.jpg');
}

footer{
  font-family: 'Open Sans', sans-serif;
}
.footer_bottom{
  background-color: #303030;
}
.footer_top a{
  color: gray;
}

span{
  color: white;
}



</style>