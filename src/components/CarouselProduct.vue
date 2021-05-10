<template>
    <div>
        <section class="women-banner spad">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-lg-12 mt-5">
                        <carousel class="product-slider" :nav="false" :item="3" :autoplay="true" :dots="false">
                            <div class="product-item">
                                <div class="pi-pic">
                                    <img src="img/product-1.jpg" alt="" />
                                    <ul>
                                        <li class="w-icon active">
                                            <a href="#"><i class="icon_bag_alt"></i></a>
                                        </li>
                                        <li class="quick-view">
                                            <router-link to="/Product">
                                                + Quick View
                                            </router-link>
                                        </li>
                                    </ul>
                                </div>
                                <div class="pi-text">
                                    <div class="catagory-name">Scarf</div>
                                    <router-link to="/Product">
                                    <a href="#">
                                        <h5>Patera</h5>
                                    </a>
                                    </router-link>
                                    <div class="product-price">
                                        $15.00
                                        <span>$25.00</span>
                                    </div>
                                </div>
                            </div>
                            <div class="product-item">
                                <div class="pi-pic">
                                    <img src="img/product-2.jpg" alt="" />
                                    <ul>
                                        <li class="w-icon active">
                                            <a href="#"><i class="icon_bag_alt"></i></a>
                                        </li>
                                        <li class="quick-view"><a href="#">+ Quick View</a></li>
                                    </ul>
                                </div>
                                <div class="pi-text">
                                    <div class="catagory-name">Scarf</div>
                                    <a href="#">
                                        <h5>Puspa</h5>
                                    </a>
                                    <div class="product-price">
                                        $15.00
                                    </div>
                                </div>
                            </div>
                            <div class="product-item">
                                <div class="pi-pic">
                                    <img src="img/product-3.jpg" alt="" />
                                    <ul>
                                        <li class="w-icon active">
                                            <a href="#"><i class="icon_bag_alt"></i></a>
                                        </li>
                                        <li class="quick-view"><a href="#">+ Quick View</a></li>
                                    </ul>
                                </div>
                                <div class="pi-text">
                                    <div class="catagory-name">Scarf</div>
                                    <a href="#">
                                        <h5>Tirta</h5>
                                    </a>
                                    <div class="product-price">
                                        $15.00
                                    </div>
                                </div>
                            </div>
                            <div class="product-item">
                                <div class="pi-pic">
                                    <img src="img/product-4.jpg" alt="" />
                                    <ul>
                                        <li class="w-icon active">
                                            <a href="#"><i class="icon_bag_alt"></i></a>
                                        </li>
                                        <li class="quick-view"><a href="#">+ Quick View</a></li>
                                        <li class="w-icon">
                                            <a href="#"><i class="fa fa-random"></i></a>
                                        </li>
                                    </ul>
                                </div>
                                <div class="pi-text">
                                    <div class="catagory-name">Scarf</div>
                                    <a href="#">
                                        <h5>Bara</h5>
                                    </a>
                                    <div class="product-price">
                                        $15.00
                                    </div>
                                </div>
                            </div>
                        </carousel>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>

import carousel from 'vue-owl-carousel';

export default {
  name: 'CaroueselProduct',
  props: {
    msg: String
  },
  components: {
    carousel
    // HelloWorld
  }
}
</script>

<style scoped>
.product-item{
    margin-right: 25px;
}
</style>