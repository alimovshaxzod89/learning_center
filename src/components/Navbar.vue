<template>
    <div>
        <div class="container d-flex justify-content-between w-100">
            <div class="navbar_logo w-25">
                <img src="@/assets/img/logo.png" alt="">
            </div>
            <div class="navbar_menues d-flex w-75">
                <p> 
                    <a href="#">Home</a> 
                </p>
                <p>
                    <a href="#">About Us</a>
                </p>
                <p>
                    <a href="#">Services</a>
                </p>
                <p>
                    <a href="#">Products</a>
                </p>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.navbar_menues p{
    font-size: 16px;
    line-height: 28px;
    font-weight: 400;
    font-family: 'Inter', sans-serif;
    padding: 30px;   
}
a{
    text-decoration: none;
    color: #1E1F4B;
}
.navbar_menues{
    transform: translateX(10%);
}

.navbar_logo img{
    width: 77px;
    height: 36px;
    margin-top: 30px;
}
</style>