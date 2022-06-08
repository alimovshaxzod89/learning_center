<template>
    <div>
        <Navbar />
        <div class="main_head container d-flex justify-content-between">
            <div class="left_section">
                <h1>We Design Impactful Digital <span class="word_products">Products</span> </h1>
                <div class="left_section__text">
                    <p>Help find solutions with intitutive and in accordance with client business goals. we provide a high-quality services.</p>
                </div>
                <div class="btn_and_player d-flex justify-content-between">
                    <button class="my_btn">Contact Us</button>
                    <div class="player d-flex justify-content-center">
                        <div class="my_player"></div>
                        <div class="players_text">
                            <p>Watch our <br> introduction video</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="right_section">
                <img src="@/assets/img/headeringirl.png" alt="">
            </div>
        </div>
    </div>
</template>
<script>
import Navbar from '@/components/Navbar.vue'
export default {
    components:{
        Navbar,
    }
}
</script>
<style scoped>
.right_section{
    width: 546px;
    height: 631px;
}
.right_section img{
    width: 531px;
    height: 531px;
}
.left_section h1{
    font-family: 'Poppins', sans-serif;
    font-size: 60px;
    font-weight: 700;
    line-height: 110px;
    letter-spacing: 0.2px;
    /* transform: translateY(30%); */
    margin-top: 10%;
}
.word_products{
    color: #706FE5;
    border: 8px solid #706FE5;
    padding: 7px 33px;
    border-radius: 8px;
    position: relative;
}
/* circle */
/* .word_products::before{
    content: '';
    position: absolute;
    right: 0;
    top: 0;
    width: 28px;
    height: 28px;
    border-radius: 50%;
    background-color: #ffffff;
    border: 8px solid #706FE5;
} */
.left_section__text{
    width: 555px;
    height: 108px;
}
.left_section__text p{
    color: #2E3E5C;
    font-family: 'Poppins', sans-serif;
    opacity: 0.8;
    font-weight: 400;
    line-height: 36px;
    font-size: 20px;
}
.btn_and_player{
    width: 450px;
    margin-top: 5%;
}
.my_btn{
    border: none;
    background-color: #706FE5;
    color: white;
    border-radius: 12px;
    height: 50%;
    padding: 10px 40px;
}

.my_player{
    width: 48px;
    height: 48px;
    background-color: rgb(236, 221, 255);
    border-radius: 50%;
    margin-right: 20px;
    position: relative;
}
.my_player::before{
    content: '';
    position: absolute;
    width: 40%;
    height: 40%;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    /* clip-path: polygon(43% 0, 42% 100%, 100% 51%); */
    clip-path: polygon(20% 0, 19% 100%, 100% 51%);
    background-color: #706FE5;
}
.players_text{
    font-family: 'Poppins', sans-serif;
    font-size: 16px;
    font-weight: 400px;
    line-height: 24px;
    color: #2E3E5C;
}
</style>