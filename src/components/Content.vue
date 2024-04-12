<template>
    <div class="contentWrapper">
        <h3>Content</h3>
    </div>    
</template>
<script>
    export default{
        name: "Content",
    };

</script>
<style scoped>
 .contentWrapper {
    height: calc(100vh - 77px);
    flex: 2;
    display: flex;
    flex-direction: column;
    background-color: rgb(179, 175, 175);
 }

</style>