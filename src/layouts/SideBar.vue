<template>
    <nav id="side-bar">
        <router-link to="/guilds">Guilds</router-link>
        <router-link to="/resources">Resources</router-link>
    </nav>
</template>

<script lang="ts">
    import Vue from 'vue'

    export default Vue.extend({
    })
</script>

<style lang="scss" scoped>
    @import "var";

    nav {
        background-color: $ftc-black;
        width: 15%;
        height: calc(100% - #{$header-height});
        padding-top: $header-height;
        float: left;
        clear: both;

        a {
            display: inline-block;
            width: calc(100% - 20px);
            color: $ftc-white;
            font-weight: bold;
            font-size: 18px;
            text-decoration:none;
            margin: 10px;

        }

        a:hover {
            text-decoration: underline;
        }
    }

</style>
