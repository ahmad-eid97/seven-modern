<template>
    <section class="footer">
    <div class=" d-flex justify-content-around pt-5 responsive-footer">
      <div class="w-30 mt-2 w-control">
        <img class="img-fluid" src="https://the7.io/modern-business/wp-content/uploads/sites/53/2019/06/7-mb-bottom-art.gif" alt="">
        <p class="text-light my-2 fs-5">Nam id sem quis mauris porttitor conse quat id vitae dolor – mauris lorem ipsum
          nulla it amet ultricies mi dolor at pharetra.</p>
        <button class="btn test-btn mt-3">Get in touch!</button>
      </div>

      <div class="text-light  w-30 mt-2 w-control">

        <h5 class="fw-bold mb-4">Contact info</h5>
        <p class="my-3 footer-text"> Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus
          mus. </p>

        <p class=""> Phone number</p>
        <p class="footer-text"> +001 234 56 78</p>

        <p class=""> Email</p>
        <p class="footer-text">hello@dream-theme.com</p>

        <p class=""> Address</p>
        <p class="footer-text">Highland St. Tonawanda, NY 14150</p>

        <div class="d-flex d-none d-lg-flex d-md-none ">
          <div class="footer-icon fs-12"> <font-awesome-icon icon="fa-brands fa-facebook-f" /> </div>
          <div class="footer-icon fs-12"> <font-awesome-icon icon="fa-brands fa-twitter" /></div>
          <div class="footer-icon fs-12"> <font-awesome-icon icon="fa-brands fa-google" /></div>
        </div>
      </div>


      <div class="w-30 mt-2 w-control">

        <h5 class="text-light fw-bold mb-4">Recent posts</h5>

        <div>
          <div class="d-flex">
            <img class="footer-article-img" src="/assets/images/im001.jpg" alt="">
            <div class="ms-2">
              <p class="text-light my-0">Glavrida sit amet – post with side images</p>
              <p class="footer-text my-0"> 16th November 2018</p>
            </div>
          </div>
          <div class="d-flex mt-4">
            <img class="footer-article-img" src="/assets/images/im001.jpg" alt="">
            <div class="ms-2">
              <p class="text-light my-0">Glavrida sit amet – post with side images</p>
              <p class="footer-text my-0"> 16th November 2018</p>
            </div>
          </div>
          <div class="d-flex mt-4">
            <img class="footer-article-img " src="/assets/images/im001.jpg" alt="">
            <div class="ms-2">
              <p class="text-light my-0">Glavrida sit amet – post with side images</p>
              <p class="footer-text my-0"> 16th November 2018</p>
            </div>
          </div>
          <div class="d-flex mt-4">
            <img class="footer-article-img" src="/assets/images/im001.jpg" alt="">
            <div class="ms-2">
              <p class="text-light my-0">Glavrida sit amet – post with side images</p>
              <p class="footer-text my-0"> 16th November 2018</p>
            </div>
          </div>
        </div>
      </div>


    </div>

    <div class="footer-border footer-text">
      <img src="https://the7.io/modern-business/wp-content/uploads/sites/53/2019/06/l-small.png" alt="">
      <p>© The7 Gutenberg Business - 2018-2019. All rights reserved.</p>

    </div>
  </section>
</template>

<script>


export default {
    name: 'AppFooter',
    components: {},
    data() {
        return {
            
        }
    },
    beforeMount () {
        
    },
    methods : {
        
    }
}
</script>

<style>
.footer {
  padding: 0;
}
.footer .btn {
  background-color: var(--main-color);
  border-color: var(--main-color);
  border-radius: 20px;
  color: #fff;
}
.footer-border {
  width: 100% !important;
  background-color: #353b43;
  margin: 30px 0  0!important;
}
.footer-border p{
  color: #fff;
  margin: 10px 0;
}
</style>