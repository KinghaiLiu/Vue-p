<template>
    <v-header></v-header>
    <router-view></router-view>
    <v-footer></v-footer>
</template>

<script>
import Cheader from './home/header.vue';
import Cfooter from './home/footer.vue';
export default {
    components: {
        'v-header': Cheader,
        'v-footer': Cfooter
    }
}
</script>

<style>
    
</style>