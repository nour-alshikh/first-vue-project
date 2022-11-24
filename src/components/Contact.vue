<template>
    <div class="contact">
        <div class="container">
            <h1 class="title text-center">CONTACT ME</h1>
            <form class=" w-75 m-auto">
                <label class="d-block mt-5">Name</label>
                <input type="text" class="w-100 mt-4 bg-light p-2">
                <label class="d-block mt-5">Email Address</label>
                <input type="text" class="w-100 mt-4 bg-light p-2">
                <label class="d-block mt-5">Phone Number</label>
                <input type="text" class="w-100 mt-4 bg-light p-2">
                <label class="d-block mt-5">Message</label>
                <input type="text" class="w-100 mt-4 bg-light p-2 mb-3">
                <button class="btn btn-outline-success my-5 py-2 px-4">Send</button>
            </form>
        </div>
    </div>
</template>

<style scoped>
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
    input{
        outline: none;
        border: none;
        border-bottom: 1px solid #111;
    }
</style>