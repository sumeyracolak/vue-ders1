<script setup>
    import { RouterLink, RouterView } from 'vue-router'
</script>
<template>
    <footer>
        <ul>
            <li><a href="#">Hakkımızda</a></li>
            <li><a href="#">İletişim</a></li>
            <li><a href="#">Gizlilik Politikası</a></li>
            <li><a href="#">Kullanım Şartları</a></li>
        </ul>
    </footer>
</template>
<style scoped lang="scss">
    footer{
        position: absolute;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: #333;
        ul{
            margin: 0;
            padding: 0;
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 20px;
            
            a{
                color: #fff;
                padding: 5px;
                display: block;
            }
        }
    }
</style>