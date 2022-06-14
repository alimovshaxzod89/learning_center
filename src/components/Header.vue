<template>
    <div>
        <Navbar />
        <div class="main_head container w-100 d-flex justify-content-between">
            <div class="left_section">
                <h1>We Design Impactful <br> Digital <span class="word_products">Products</span> </h1>
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
    position: relative;
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


/* Media */

@media only screen and (max-width: 1400px) {
.left_section h1{
    font-size: 40px;
    line-height: 90px;
}
.left_section__text{
    width: 480px;
    height: 80px;
}
.left_section__text p{
    font-weight: 400;
    line-height: 30px;
    font-size: 16px;
}
  .right_section img{
    width: 400px;
    height: 400px;
    margin-left: 15%;
  }
}
@media only screen and (max-width: 1000px) {
    .main_head{
        overflow: hidden;
    }
    .right_section{
        width: 45%;
    }
    .left_section{
        width: 48%;
    }

    .left_section h1{
        font-size: 28px;
        line-height: 60px;
    }
    .left_section__text{
        width: 100%;
        height: 40px;
    }
    .left_section__text p{
        line-height: 20px;
        font-size: 12px;
    }
    .word_products{
        padding: 4px 25px;
    }
    .right_section img{
        width: 250px;
        height: 250px;
        margin-left: 25%;
    }
    .btn_and_player{
        width: 300px;
        margin-top: 20px;
    }
    .my_btn{
        padding: 5px 20px;
        font-size: 10px;
        margin-top: 10px;
    }
    .my_player{
        width: 28px;
        height: 28px;
        margin-top: 10px;
    }
    .my_player::before{
        content: '';
        width: 30%;
        height: 30%;
    }
    .players_text{
        margin-top: 10px;
        font-size: 10px;
        line-height: 15px;
    }
    .right_section{
        height: 400px;
    }
}
@media only screen and (max-width: 770px) {
    .left_section h1{
        font-size: 20px;
        line-height: 40px;
    }
    .left_section__text{
        width: 100%;
        height: 40px;
    }
    .left_section__text p{
        line-height: 15px;
        font-size: 10px;
        margin-top: 15px;
    }
    .word_products{
        padding: 2px 20px;
    }
    .right_section img{
        width: 200px;
        height: 200px;
        margin-left: 20%;
    }
    .btn_and_player{
        width: 230px;
        margin-top: 12px;
    }
    .my_btn{
        padding: 3px 15px;
        font-size: 8px;
        margin-top: 8px;
    }
    .my_player{
        width: 25px;
        height: 25px;
        margin-top: 8px;
        margin-right: 4px;
    }
    .players_text{
        margin-top: 9px;
        font-size: 7px;
        line-height: 10px;
    }
    .right_section{
        height: 300px;
    }
}
@media only screen and (max-width: 492px) {
    .left_section h1{
        font-size: 18px;
        line-height: 35px;
    }
    .left_section__text{
        width: 100%;
        height: 40px;
    }
    .left_section__text p{
        margin-top: 15px;
        line-height: 10px;
        font-size: 8px;
    }
    .word_products{
        padding: 1px 15px;
    }
    .right_section img{
        width: 180px;
        height: 180px;
        margin-left: 10%;
    }
    .btn_and_player{
        width: 150px;
        margin-top: 8px;
    }
    .my_btn{
        padding: 2px 10px;
        font-size: 5px;
        margin-top: 5px;
    }
    .my_player{
        width: 20px;
        height: 20px;
        margin-top: 0px;
        margin-right: 4px;
    }
    .players_text{
        margin-top: 2px;
        font-size: 5px;
        line-height: 8px;
    }
    .right_section{
        height: 250px;
    }
}
@media only screen and (max-width: 437px) {
    
    .left_section h1{
        font-size: 14px;
        line-height: 28px;
    }
    .left_section__text p{
        line-height: 7px;
        font-size: 5px;
    }
    .word_products{
        padding: 0px 10px;
    }
    .right_section img{
        width: 150px;
        height: 150px;
        margin-left: 15%;
    }
    .btn_and_player{
        margin-top: 0px;
    }
    .my_btn{
        padding: 2px 10px;
        font-size: 5px;
        margin-top: 0px;
    }
    .my_player{
        margin-top: -5px;
    }
    .players_text{
        margin-top: -3px;
    }
    .right_section{
        height: 200px;
    }
}

</style>