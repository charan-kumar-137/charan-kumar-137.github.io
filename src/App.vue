<template>
    <div>
        <AppHeader></AppHeader>
        <AppBanner></AppBanner>
        <AppProjects></AppProjects>
        <AppFooter></AppFooter>
    </div>

</template>

<script>
    import AppHeader from './components/Header.vue'
    import AppBanner from './components/Banner.vue'
    import AppProjects from './components/Projects.vue'
    import AppFooter from './components/Footer.vue'

    export default {
        name: 'App',
        components: {
            AppHeader,
            AppBanner,
            AppProjects,
            AppFooter
        }
    }
</script>

<style>
    @import './assets/css/responsive.css';
    @import './assets/css/styles.css';
</style>