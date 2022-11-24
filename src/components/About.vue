<template>
    <div class="about">
        <div class="container">
            <h1 class="title text-white">ABOUT</h1>
            <div class="row justify-content-center">
                <div class="col-md-6 text-white ">
                    <div class="item text-end mb-5">
                        <h4 class="text-start px-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, provident! Quae aut odio sit libero.
                            Vitae illum sint aliquid. Illum quod eos consequuntur impedit libero in dolorem alias quidem voluptas.
                        </h4>
                    </div>
                </div>
                <div class="col-md-6 text-white">
                    <div class="item">
                        <h4 class="text-start px-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, provident! Quae aut odio sit libero.
                            Vitae illum sint aliquid. Illum quod eos consequuntur impedit libero in dolorem alias quidem voluptas.
                        </h4>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.about{
        background-color: rgb(12, 194, 134);
        padding-top: 40px;
        padding-bottom: 40px;
        text-align: center;
        position: relative;
    }

.title::before {
    content: "";
    background-color: white;
    width: 7%;
    height: 3px;
    position: absolute;
    bottom: -35px;
    left: 50%;
    transform: translateX(-50%);
}
.title{
    position: relative;
    margin-bottom: 80px;
}

</style>