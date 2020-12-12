<template>
<ul>
        <li>
            <a href="/">Home</a>
        </li>
        <li>
            <a href="/">Contact Us</a>
        </li>
        <li>
            <a href="/">About US</a>
        </li>
        <li>
            <a href="/">Our Team</a>
        </li>
    </ul>
</template>

<script>
export default {
    name: 'vue-menu'
}
</script>

<style scoped>
ul, li {
    padding: 0;
    margin: 0;
    font-size: 30px;
}

ul {
    background-color: rgb(228, 96, 188);
    display: flex;
    flex-direction:row;
    justify-content: space-between;
    list-style-type: none;
}
</style>

