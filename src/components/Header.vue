<template>
    <div class="header">
        <img src="../../src/assets/header_logo.png">
        <ul class="navi-menu">
            <li><a href="#about">ABOUT</a></li>
            <li><a href="#course">COURSE</a></li>
            <li><a href="#news">NEWS</a></li>
            <li><a href="#access">ACCESS</a></li>
            <li><a href="#contact">CONTACT</a></li>
        </ul>
    </div>

</template>

<script>
export default {
    
}
</script>

<style scoped>
.header{
    display: flex;
    justify-content: space-between;
}

.header img{
    margin-top: 20px;
}

.navi-menu{
    display: flex;
    list-style: none;
}

.navi-menu li {
    text-align: center;
    /* height: 50px; */
    /* line-height: 50px; */
    margin-right: 2px;
    /* margin-top: 50px; */
    font-size: 21px;
    margin-left: 80px;
    margin: 50px 0 0 50px;
}

.navi-menu li a {
    color: black;
    text-decoration: none;
}
</style>