<template>
    <div>
        <div>
            <h2 class="title">Let's hear <br> What they says</h2>
        </div>
        <div class="text mt-5">
            <p class="w-50 m-auto">
                Dolor sit amet consectetur adipisicing elit. Magni repellendus eligendi impedit nihil nemo pariatur, alias, obcaecati ab omnis in voluptates incidunt consectetur libero inventore doloremque iste exercitationem possimus asperiores.
            </p>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.title{
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
    font-size: 40px;
    line-height: 60px;
    text-align: center;
    position: relative;
}
.text p{
    font-family: 'Poppins', sans-serif;
    font-weight: 400;
    font-size: 16px;
    line-height: 50px;
    text-align: center;
    opacity: .5;
}
.title::before{
    content: url('@/assets/img/string.png');
    position: absolute;
    top: 50%;
    left: 20%;
}
.title::after{
    content: url('@/assets/img/string.png');
    position: absolute;
    top: 50%;
    right: 20%;
}
</style>