<template>
  <nav class="navigation">
    <ul>
      <li>
        <a href="#">Categorias</a>
        <a href="#">Ofertas</a>
        <a href="#">Historial</a>
        <a href="#">Supermercado</a>
        <a href="#">Moda</a>
        <a href="#">Vender</a>
        <a href="#">Ayuda / PQR</a>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
.navigation {
  bottom: 0;
}

.navigation ul li {
  list-style: none;
}
.navigation ul li a {
  text-decoration: none;
  font-size: 1.4rem;
  margin-right: 1.2rem;
  color: rgba(51, 51, 51, 0.6);
  transition: color .3s ease-out;
}

.navigation ul li a:hover {
  color: #333333;
}

.navigation ul li a:last-child {
    margin: 0;
}
</style>