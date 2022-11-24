<template>
    <h1 class="title text-center py-5 mb-3">PORTFOLIO</h1>
    <div class="container">
        <div class="row">
            <div class="col-md-4 mb-5">
                <div class="item">
                    <img class="w-100 rounded-3" src="cabin.png" alt="">
                </div>
            </div>
            <div class="col-md-4 mb-5">
                <div class="item">
                    <img class="w-100 rounded-3" src="cake.png" alt="">
                </div>
            </div>
            <div class="col-md-4 mb-5">
                <div class="item ">
                    <img class="w-100 rounded-3" src="circus.png" alt="">
                </div>
            </div>
            <div class="col-md-4 mb-5">
                <div class="item">
                    <img class="w-100 rounded-3" src="game.png" alt="">
                </div>
            </div>
            <div class="col-md-4 mb-5">
                <div class="item">
                    <img class="w-100 rounded-3" src="safe.png" alt="">
                </div>
            </div>
            <div class="col-md-4 mb-5">
                <div class="item">
                    <img class="w-100 rounded-3" src="submarine.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    img{
        cursor: pointer;
    }
    .title{
        position: relative;
        padding: 90px;
        padding-bottom: 30px;
        width: fit-content;
        margin: auto;
    }
    .title::before{
        content: "";
        width: 37%;
        height: 3px;
        background-color: black;
        position: absolute;
        bottom: 0;
        left: 50%;
        transform: translateX(-50%);
    }
</style>