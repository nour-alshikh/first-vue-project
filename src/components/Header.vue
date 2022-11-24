<template>
<nav>
    <div class="py-4 px-5 d-flex justify-content-center justify-content-md-between align-items-center">
        <div class="logo">
            START VUEJS
        </div>
        <ul class="links justify-content-center align-items-center m-0 d-none d-md-flex">
            <li class="px-3"><a class="text-white text-decoration-none" href="#">PORTFOLIO</a></li>
            <li class="px-3"><a class="text-white text-decoration-none" href="#">ABOUT</a></li>
            <li class="px-3"><a class="text-white text-decoration-none" href="#">CONTACT</a></li>
        </ul>
    </div>
</nav>

</template>


<style scoped>
    ul{
        list-style: none;
        padding: 0;
        margin-bottom: 0;
    }
    a{
        text-decoration: none;
        font-size: 25px;
        color: white;
        cursor: pointer;
    }
    a:hover{
        text-decoration: none;
        font-size: 25px;
        color: white;
    }
    .logo{
        color: white;
        font-size: 30px;
    }
    nav{
        background-color: darkslategray;
        height: 100px;
        font-weight: 600;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        z-index: 999;
    }
</style>


