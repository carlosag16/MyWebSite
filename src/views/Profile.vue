<template>
    <div class="profile-page">
        <section class="section-profile-cover section-shaped my-0">
            <div class="shape shape-style-1 shape-primary shape-skew alpha-4">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
        </section>
        <section class="section section-skew">
            <div class="container">
                <card shadow class="card-profile mt--300" no-body>
                    <div class="px-4">
                        <div class="row justify-content-center">
                            <div class="col-lg-3 order-lg-2">
                                <div class="card-profile-image">
                                    <router-link to="/">
                                        <img v-lazy="'img/theme/carlos.jpg'" class="rounded-circle">
                                    </router-link>
                                </div>
                            </div>
                            <div class="col-lg-4 order-lg-3 text-lg-right align-self-lg-center">
                                <div class="card-profile-actions py-4 mt-lg-0">
                                    <!-- <base-button type="info" size="sm" class="mr-4">Connect</base-button> -->
                                    <base-button type="default" size="sm" class="float-right">Message</base-button>
                                </div>
                            </div>
                            <div class="col-lg-4 order-lg-1">
                                <div class="card-profile-stats d-flex justify-content-center">
                                    <div>
                                        <router-link to="/#meus">
                                        <span class="heading">5</span>
                                        <span class="description" style="color: #000">Projetos</span>
                                        </router-link>
                                    </div>
                                    <!-- <div>
                                        <span class="heading">10</span>
                                        <span class="description">Photos</span>
                                    </div>
                                    <div>
                                        <span class="heading">89</span>
                                        <span class="description">Comments</span>
                                    </div> -->
                                </div>
                            </div>
                        </div>
                        <br>
                        <div class="text-center mt-5">
                            <h3>Carlos Nascimento
                                <span class="font-weight-light">,</span>
                            </h3>
                            <div class="h6 font-weight-300"><i class="ni location_pin mr-2"></i>Belém, Brasil</div>
                            <div class="h6 mt-4"><i class="ni business_briefcase-24 mr-2"></i>Desenvolvedor Web</div>
                            <div><i class="ni education_hat mr-2"></i>Engenharia da computação - UFPA</div>
                        </div>
                        <div class="mt-5 py-5 border-top text-center">
                            <div class="row justify-content-center">
                                <div class="col-lg-9">
                                    <p>An artist of considerable range, Ryan — the name taken by Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and records all of his own music, giving it a warm, intimate feel with a solid groove structure. An artist of considerable range.</p>
                                </div>
                            </div>
                            <split-carousel>
                                <split-carousel-item >
                                    <b-img src="img/theme/download.png" fluid alt="Responsive image"></b-img>
                                </split-carousel-item>
                            </split-carousel>
                        </div>
                        
                    </div>
                </card>
                
            </div>
            
        </section>
        <h1 class="tiitulo" id="meus">Meus projetos</h1>
    </div>
</template>
<script>

import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  components: { 
    BCarousel,
    BCarouselSlide,
    
  },
  };
</script>
<style>
.tiitulo{
    text-align: center;
    color: #8b008b;
}
</style>
