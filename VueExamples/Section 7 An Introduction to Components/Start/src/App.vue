<template>
    <div class="container">
        <appHeader></appHeader>
        <hr>
        <div class="row">
            <servers></servers>
            <app-server-details></app-server-details>
        </div>
        <hr>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import Header from './components/shared/Header.vue';
    import Footer from './components/shared/Footer.vue';
    import Servers from './components/server/Servers.vue';
    import ServerDetails from './components/server/ServerDetails.vue';

    export default {
        components: {
            appHeader: Header,
            //'app-servers': Servers,
            Servers,
            'app-server-details': ServerDetails,
            'app-footer': Footer
        }
    }
</script>

<style>

</style>
