<template>
  <div class="ubicacion">
    <i class="fas fa-map-marker-alt"></i>
    <div class="info-text-ubicacion">
      <span>Ingresa tu</span>
      <span>ubicación</span>
    </div>
  </div>
</template>

<style scoped>
.ubicacion {
  width: auto;
  display: flex;
  align-items: center;
}

.ubicacion i {
    font-size: 2rem;
    font-weight: 300;
    margin-right: 1rem;
    color: #333333;
}

.info-text-ubicacion {
    display: flex;
  flex-direction: column;
}

.info-text-ubicacion span {
    font-size: 1.4rem;
    color: #333333;
}
</style>