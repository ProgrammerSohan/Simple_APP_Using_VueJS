<template>
    <div class="wrapper">
        <Header />
        <div class="bottomWrapper"></div>
    </div>
    
</template>
<script>

import Header from "./components/Header.vue";
export default {
    name: "App",
    components: {
        Header,
    },

};

</script>
<style>
html,
body{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.wrapper{
    display: flex;
    flex-direction: column;
}
.bottomWrapper {
    display: flex;
}

</style>