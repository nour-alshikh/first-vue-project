<template>
<div class="landing d-flex justify-content-center align-items-center flex-column">
    <div class="image">
    <img src="avataaars.svg" alt="">
    </div>
    <h1 class="text-white">START VUE JS</h1>
    <h4 class="text-white">Graphic Artist - Web Designer - Illustrator</h4>
</div>
</template>

<style scoped>
.landing{
    background-color: rgb(12, 194, 134);
    width: 100%;
    height: 100vh;
}
.image{
    width: 200px;
}
h1{
    font-size: 50px;
    margin-top: 20px;
    margin-bottom: 50px;
    position: relative;
}
h1::before{
    content: "";
    background-color: white;
    width: 70%;
    height: 3px;
    position: absolute;
    bottom: -35px;
    left: 50%;
    transform: translateX(-50%);
}

</style>