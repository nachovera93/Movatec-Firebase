<template>
    <section class="section section-lg section-shaped overflow-hidden my-0">
        <div class="shape shape-style-1  shape-skew">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <div class="container py-0 pb-lg">
            <div class="row justify-content-between align-items-center">
                <div class="col-lg-5 mb-5 mb-lg-0">
                    <h1 class=" font-weight-light">Reportes a medida</h1>
                    <p class="lead mt-4">Visualizar informes con la ocupación del bot seleccionado. La cantidad total de mensajes enviados a su bot en un período determinado. La cantidad promedio de mensajes por chat enviados a su bot en un período determinado y la personalización de estos informes</p>
                    <a href=""
                       class="btn btn-white mt-4">Averiguar</a>
                </div>
                <div class="col-lg-6 mb-lg-auto">
                    <div class="rounded shadow-lg overflow-hidden transform-perspective-right">
                        <b-carousel id="carousel1"
                                    controls
                                    indicators>
                            <!-- Text slides with image -->
                            <b-carousel-slide img-src="https://www.chatbot.com/images/help/reports/reports-overview/reports-overview-3.png"></b-carousel-slide>
                            <b-carousel-slide img-src="https://www.chatbot.com/images/help/reports/reports-overview/reports-overview-7.png"></b-carousel-slide>
                            <b-carousel-slide img-src="https://www.chatbot.com/images/help/reports/reports-overview/reports-overview-10.png"></b-carousel-slide>
                        </b-carousel>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import { BCarousel } from "bootstrap-vue/esm/components/carousel/carousel";
import { BCarouselSlide } from "bootstrap-vue/esm/components/carousel/carousel-slide";

export default {
  components: {
    BCarousel,
    BCarouselSlide
  }
};
</script>
<style>
</style>
