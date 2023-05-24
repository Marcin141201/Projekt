<template>
    <div class="nav">

        <NuxtLink class="nav-item" to="/">Nowości</NuxtLink>
        <NuxtLink class="nav-item" to="/męskie">Męskie</NuxtLink>
        <NuxtLink class="nav-item" to="/damskie">Damskie</NuxtLink>
        <NuxtLink class="nav-item" to="/akcesoria">Akcesoria</NuxtLink>


    </div>
</template>

<style scoped>

.nav
{
    background-color: black;
    display: flex;
    min-height: 30px;
    padding: 15px;
    border-bottom: 5px solid yellow;
    justify-content: center;
    box-shadow: 0px 5px 12px 0px #a2a2a2;
    grid-template-columns: 64px min-content 1fr min-content min-content min-content min-content 1fr min-content 64px;
    grid-template-rows: 1fr;
}
.nav-item
{
    padding: 20px 5px 10px 5px;
    color: white;
    text-decoration: none;
    cursor: pointer;
    font-size: 20px;
}
.nuxt-link-exact-active, .nav-item:hover
{
    background-color: white;
    color: black;
}
@media screen and (max-width: 1024px) {
    .nav {
    flex-wrap: wrap;
    justify-content: space-evenly;
    }
    .nav-item {
    padding: 10px;
    }
}
@media screen and (max-width: 640px) {
    .nav {
    flex-direction: column;
    }
    .nav-item {
    padding: 10px 5px;
    }
}



</style>

