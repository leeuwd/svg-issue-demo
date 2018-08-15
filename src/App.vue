<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/logo.png">
        <div style="margin-top: 3rem; background: lightgray; min-height: 10rem;">
            <TwitterLogoSvg/>
        </div>
    </div>
</template>

<script>
    import HelloWorld from './components/HelloWorld.vue';
    // eslint-disable-next-line import/extensions
    import TwitterLogoSvg from './assets/twitter.svg?inline';

    export default {
        name: 'app',
        components: {
            HelloWorld,
            TwitterLogoSvg,
        },
    };
</script>

<style lang="scss">
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
