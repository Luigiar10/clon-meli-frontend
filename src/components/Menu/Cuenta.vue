<template>
    <div class="acceso-cuenta">
        <ul>
            <li>
                <a href="#">Crea tu cuenta</a>
                <a href="#">Ingresa</a>
                <a href="#">Mis compras</a>
                <a href="#">
                    <i class="fas fa-cart-plus"></i>
                </a>
            </li>
        </ul>
    </div>
</template>

<style scoped>
.acceso-cuenta ul li {
    list-style: none;
}

.acceso-cuenta ul li a {
    text-decoration: none;
    font-size: 1.4rem;
    color: #333333;
    margin-right: 1.7rem;
}

.acceso-cuenta ul li a span {
    font-weight: 300;
}

.acceso-cuenta ul li a:last-child {
    margin: 0;
}
</style>