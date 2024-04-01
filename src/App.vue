import router from './router';
<template>
  <header>
    <router-link :to="{ name: 'home' }">Home</router-link> |
    <router-link to="/categorias">Categorias</router-link>
    <router-link to="/acessorio">Acessorios</router-link> 
    <router-link to="/cor">Cores</router-link>  
    <router-link to="/marca">Marcas</router-link> 
  </header>
  <main>
    <RouterView />
  </main>
</template>
