<template>
    <div class="content-wrapper">
        <h2 class="title-header">Logo's Page</h2>
        <div class="item-content">
            <img class="logo" alt="Abstract logo" src="../assets/abstract.jpg">
        </div>
        <div class="item-content">
            <img class="logo" alt="Logoname logo" src="../assets/logoname.jpg">
        </div>
        <div class="item-content">
            <img class="logo" alt="Phoenix logo" src="../assets/phoenix.jpg">
        </div>
        <div class="item-content">
            <img class="logo" alt="Abstract logo" src="../assets/abstract.jpg">
        </div>
        <div class="item-content">
            <img class="logo" alt="Logoname logo" src="../assets/logoname.jpg">
        </div>
        <div class="item-content">
            <img class="logo" alt="Phoenix logo" src="../assets/phoenix.jpg">
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FirstComponent'
    }
</script>

<style scoped>
    .title-header {
        margin-bottom: 80px;
        text-align: left;
    }
    .content-wrapper {
        width: 62%;
        overflow: hidden;
        margin: auto;
    }
    .item-content {
        float: left;
        margin-right: 70px;
        margin-bottom: 70px;
        width: 150px;
        height: 150px;
    }
    .item-content .logo {
        width: 150px;
        height: 150px;
    }
</style>