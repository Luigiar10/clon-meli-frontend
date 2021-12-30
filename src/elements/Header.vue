<template>
  <header>
    <div class="navigation-header">
      <div class="bloque-one">
        <Logo />
        <Ubicacion />
      </div>
      <div class="bloque-two">
        <Search />
        <Nav />
      </div>
      <div class="bloque-three">
        <Promo />
        <Cuenta />
      </div>
    </div>
  </header>
</template>

<script>
import Logo from "@/components/Menu/Logo";
import Ubicacion from "@/components/Menu/Ubicacion";
import Search from "@/components/Menu/Search";
import Nav from "@/components/Menu/Nav";
import Promo from "@/components/Menu/Promo";
import Cuenta from "@/components/Menu/Cuenta";

export default {
  components: {
    Logo,
    Ubicacion,
    Search,
    Nav,
    Promo,
    Cuenta
  },
};
</script>

<style scoped>
header {
  width: 100vw;
  height: auto;
  background-color: #fff159;
}

.navigation-header {
  width: 100%;
  max-width: 120rem;
  margin: 0 auto;
  padding: 1rem 0;
  display: flex;
  /* align-items: center; */
  justify-content: space-between;
}

.bloque-two {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.bloque-three {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: space-between;
}
</style>