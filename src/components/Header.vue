<script setup>
    import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
    <header>
        <RouterLink to="/">Anasayfa</RouterLink>
        <RouterLink to="/about">Hakkımızda</RouterLink>
      </header>
</template>
<style scoped lang="scss">
    header{
        position: absolute;
        left: 0;
        top: 0;
        right: 0;
        display: flex;
        padding: 20px;
        gap: 20px;
        a{
            display: block;
            color: #000;
        }
    }
</style>