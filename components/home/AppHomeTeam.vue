<template>
   <section class="team-section bg-f8 text-center">
        <div class="container">
            <div class="row">
                <div class="section-title">

                    <h2>OUR TEAM</h2>

                </div>
            </div>
            <div class="row">
                <div class="col-12 slider-container">

                    <swiper :options="swiperOption" class="team">
                        <swiper-slide>
                        <div class="item">
                            <div class=" projects-col">

                                <div class="">
                                    <img src="https://the7.io/modern-business/wp-content/uploads/sites/53/2018/10/p12-400x400.jpg" alt="">
                                </div>
                                <div class="content">
                                    <h4>Alex Black</h4>
                                    <h5>Laed Programmer</h5>
                                    <h6>Donec vestibulum lectus sem, vel convallis ligula commodo ac.</h6>

                                </div>
                            </div>
                        </div>
                        </swiper-slide>

                        <swiper-slide>
                        <div class="item">
                            <div class=" projects-col">

                                <div class="">
                                    <img src="https://the7.io/modern-business/wp-content/uploads/sites/53/2018/11/p19.jpg" alt="">
                                </div>
                                <div class="content">
                                    <h4>John Brown</h4>
                                    <h5>Photographer</h5>
                                    <h6>Donec vestibulum lectus sem, vel convallis ligula commodo ac.</h6>

                                </div>
                            </div>
                        </div>
                        </swiper-slide>

                        <swiper-slide>
                        <div class="item">
                            <div class=" projects-col">

                                <div class="">
                                    <img src="https://the7.io/modern-business/wp-content/uploads/sites/53/2018/11/p22.jpg" alt="">
                                </div>
                                <div class="content">
                                    <h4>Diana Richards</h4>
                                    <h5>Lead Designer</h5>
                                    <h6>Donec vestibulum lectus sem, vel convallis ligula commodo ac.</h6>

                                </div>
                            </div>
                        </div>
                        </swiper-slide>

                        <swiper-slide>
                        <div class="item">
                            <div class=" projects-col">

                                <div class="">
                                    <img src="https://the7.io/modern-business/wp-content/uploads/sites/53/2018/11/p16.jpg" alt="">
                                </div>
                                <div class="content">
                                    <h4>Alexandra Green</h4>
                                    <h5>SMM Expert</h5>
                                    <h6>Donec vestibulum lectus sem, vel convallis ligula commodo ac.</h6>
                                </div>
                            </div>
                        </div>
                        </swiper-slide>

                        <swiper-slide>
                        <div class="item">
                            <div class=" projects-col">

                                <div class="">
                                    <img src="/assets/images/team.jpg" alt="">
                                </div>
                                <div class="content">
                                    <h4>RICHARD SWIFT</h4>
                                    <h5>junior consultant</h5>
                                    <h6>Donec vestibulum lectus sem, vel convallis ligula commodo ac.</h6>

                                </div>
                            </div>
                        </div>
                        </swiper-slide>
                    </swiper>

                    <font-awesome-icon class="next" icon="fa-solid fa-angle-right" />
                    <font-awesome-icon class="prev" icon="fa-solid fa-angle-left" />
                </div>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'AppHomeTeam',
    data() {
        return {
        swiperOption: {
            loop: true,
            slidesPerView: 5,
            spaceBetween: 50,
            breakpoints: {
            // when window width is >= 320px
            100: {
                slidesPerView: 1,
                spaceBetween: 5,
            },
            // when window width is >= 480px
            480: {
                slidesPerView: 2,
                spaceBetween: 5,
            },
            // when window width is >= 640px
            640: {
                slidesPerView: 3,
                spaceBetween: 5,
            },
            992: {
                slidesPerView: 4,
                spaceBetween: 5,
            },
            1200: {
                slidesPerView: 5,
                spaceBetween: 5,
            },
            },
        },
        }
    },
    methods : {
        
    }
}
</script>

<style>
    .team-section {
        padding: 30px;
    }
    .slider-container {
        position: relative;
    }
    .slider-container .team {
        background: #fff;
    }
    .slider-container .team .owl-item {
        padding: 50px 50px;
    }
    
    .overview-icon {
        height: 34px !important;
    }
    .overview-icon .one {
        position: static !important;
        font-size: 23px !important;
        text-align: center;
    }
    .team img {
  border-radius: 50%;
  width: 150px;
  margin-bottom: 30px;
  animation: border-transform 15s infinite ease-in-out;
}
.team .content h4 {
  color: var(--main-color);
  font-size: 20px;
  margin-bottom: 10px;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.team .content h5 {
  color: var(--main-color);
  font-size: 16px;
  margin-bottom: 20px;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.team .content h6 {
  color: #989898;
  font-family: 'Open Sans', sans-serif;
  font-size: 14px;
  text-transform: uppercase;
  margin-bottom: 15px;
  line-height: 28px;
  letter-spacing: 0.3px;
}
.team .content h5 {
  color: var(--main-color);
  font-size: 16px;
  margin-bottom: 20px;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.team .content h3 {
  color: var(--main-color);
  font-size: 16px;
  margin-bottom: 20px;
  letter-spacing: 1px;
  text-transform: uppercase;
}

.team .owl-theme .owl-nav .owl-next,
    .team .owl-theme .owl-nav .owl-next:hover, 
    .team .owl-theme .owl-nav .owl-prev, 
    .team .owl-theme .owl-nav .owl-prev:hover {
        background-color: transparent;
        display: inline-block;
        border-radius: 30px;
        bottom: 0;
        text-align: center;
        line-height: 26px;
        font-size: 20px;
        position: absolute;
        padding: 4px 11px;
        border: 1px solid var(--main-color);
        color: var(--main-color);
    }
    .team .owl-theme .owl-nav .owl-next:hover, 
    .team .owl-theme .owl-nav .owl-prev:hover {
        background: var(--main-color);
        color: #fff;
        transition: all 0.2s linear;
    }
    .team .owl-theme .owl-nav .owl-next {
        right: 45% !important;
    }
    .team .owl-theme .owl-nav .owl-prev {
        right: 50% !important;
    }
.team-area .section-title {
    margin-bottom: 0;
}
.team-area  .section-title span {
  margin-bottom: 8px;
  font-weight: 600;
  display: block;
  color: #f86011;
}
.team-area .section-title h2 {
    max-width: 600px;
    color: #252525;
    font-size: 35px;
    font-weight: 800;
    letter-spacing: -1px;
    line-height: 42px;
    text-align: left;
    margin-top: 10px;
    margin-right: auto;
    margin-bottom: 15px;
    margin-left: auto;
    text-align: center;
}
.team-area .section-title .seprator img {
    width: 70px;
    margin-top: 5px;
    margin-bottom: 20px;
}
</style>