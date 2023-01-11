<template>
<div id="menu">
    <h2>네브</h2>
    <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">about</router-link></li>
        <li><router-link to="/about/thumnail">thumnail</router-link></li>
    </ul>
</div>
</template>
<script>
export default {}
</script>
<style>
#menu {
    left: 0;
    width: 10%;
    height: 80vh;
    border: 1px solid #dedede;
}

ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

</style>