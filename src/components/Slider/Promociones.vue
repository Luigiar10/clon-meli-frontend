<template>
<div class="promos">
    <div class="imgPromo">
        <img src="https://http2.mlstatic.com/D_NQ_834383-MLA48646606610_122021-OO.webp" alt="">
    </div>
    <div class="imgPromo">
        <img src="https://http2.mlstatic.com/D_NQ_818053-MLA48701763964_122021-OO.webp" alt="">
    </div>
    <div class="imgPromo">
        <img src="https://http2.mlstatic.com/D_NQ_998012-MLA48646606082_122021-OO.webp" alt="">
    </div>
    <div class="imgPromo">
        <img src="https://http2.mlstatic.com/D_NQ_908309-MLA48646625518_122021-OO.webp" alt="">
    </div>
    <div class="imgPromo">
        <img src="https://http2.mlstatic.com/D_NQ_875063-MLA48646734013_122021-OO.webp" alt="">
    </div>
    <div class="imgPromo">
        <img class="imgWidth" src="https://http2.mlstatic.com/D_NQ_609846-MLA48712523798_122021-OO.webp" alt="">
    </div>
    <div class="controlImg">
        <div class="last" onClick="controlSlide(-1)">
            <span>&#10094</span>
        </div>
        <div class="next" onClick="controlSlide(1)">
            <span>&#10095</span>
        </div>
    </div>
    <div class="puntos">
        <span class="punto" onClick="pocisionSlide(1)"></span>
        <span class="punto" onClick="pocisionSlide(2)"></span>
        <span class="punto" onClick="pocisionSlide(3)"></span>
        <span class="punto" onClick="pocisionSlide(4)"></span>
        <span class="punto" onClick="pocisionSlide(5)"></span>
        <span class="punto" onClick="pocisionSlide(6)"></span>
    </div>
</div>
</template>

<script>
export default {
  name: "Promociones",
  methods: {
    cssPromo() {
      let promo = document.querySelector(".promos");
      let height = document.querySelector(".imgPromo");
      let pxAlto = height.clientHeight;
      promo.style.height = `${pxAlto}px`;
    },
  },

//   beforeMount() {
//     this.cssPromo();
//   },

//   created() {
//     this.cssPromo();
//   },

    mounted() {
      this.cssPromo();
      console.log(this.cssPromo());
    },
};
</script>

<style scoped>
.promos {
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
  position: relative;
}

.promos .imgPromo {
  position: absolute;
}

.promos .imgPromo img {
  width: 100%;
}

.controlImg {
  width: 100%;
  /* height: 100%; */
  position: absolute;
  height: inherit;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.controlImg span {
  margin: 2rem;
  font-size: 3rem;
}

.controlImg span:hover {
  padding: 0.5rem;
  background-color: red;
}

.puntos {
  position: absolute;
}

.punto {
  height: 0.2rem;
  width: 0.2rem;
  background-color: red;
}
</style>