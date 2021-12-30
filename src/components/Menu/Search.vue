<template>
    <div class="search-box">
        <input type="text" placeholder="Buscar productos, marcas y más...">
        <div class="search-icon">
            <p>|</p>
            <i class="fas fa-search"></i>
        </div>
    </div>
</template>

<style scoped>
.search-box{
    background-color: #ffffff;
    display: flex;
    align-items: center;
    box-shadow: 0 1px 2px rgba(0, 0, 0, .2);
}

.search-icon {
    display: flex;
    align-items: center;
}

.search-icon p {
    font-size: 3rem;
    font-weight: 100;
    margin-right: 1rem;
}

.search-icon i {
    font-size: 1.6rem;
    font-weight: 300;
    margin-right: 1.5rem;
}

.search-box input {
    width: 100%;
    padding: .8rem 1.5rem;
    outline: none;
    border: none;
    font-size: 1.6rem;
    font-weight: 300;
    min-width: 50rem;
}
</style>