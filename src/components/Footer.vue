<template>
    <div class="footer">
        <div class="footer_one container d-flex justify-content-between">
            <div class="my_white_logo">
                <img src="@/assets/img/logowhite.png" alt="">
            </div>
            <div class="s_medias d-flex">
                <div class="my_icon_group">
                    <box-icon class="my_icon" name='instagram' type='logo'  color='white'></box-icon>
                </div>
                <div class="my_icon_group">
                    <box-icon class="my_icon" type='logo' name='facebook' color='white'></box-icon>
                </div>
                <div class="my_icon_group">
                    <box-icon class="my_icon" type='logo' name='twitter' color='white'></box-icon>
                </div>
                <div class="my_icon_group">
                    <box-icon class="my_icon" name='telegram' type='logo' color='white' ></box-icon>
                </div>
                <div class="my_icon_group">
                    <box-icon class="my_icon" name='github' type='logo'  color='white'></box-icon>
                </div>
            </div>
        </div>
        <hr class="container" style="color: white;">

        <div class="footer_two container d-flex justify-content-between">
            <div class="footer_menu w-75">
                <h4>Company</h4>
                <ul>
                    <li>
                        <a href="#">About US</a>
                    </li>
                     <li>
                        <a href="#">Press</a>
                    </li>
                     <li>
                        <a href="#">Investors</a>
                    </li>
                     <li>
                        <a href="#">Events</a>
                    </li>
                     <li>
                        <a href="#">Team of use</a>
                    </li>
                     <li>
                        <a href="#">Privacy policy</a>
                    </li>
                </ul>
            </div>
            <div class="footer_btn">
                <button class="my_btn">Contact Us</button>
            </div>
        </div>  
        <div class="footer_tree text-center">
            <p class="mt-5 pb-5 text-light">© power 2021 - All Rights Reserved</p>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.footer{
    background-color: #2E3E5C;
    margin-top: 10%;
}
.footer_one{
    padding: 55px 0;
}
.my_white_logo{
    width: 77px;
    height: 36px;
}
.my_white_logo img{
    width: 100%;
    height: 100%;
}
.my_icon_group{
    width: 48px;
    height: 48px;
    background-color: #706FE5;
    color: white;
    border-radius: 50%;
    position: relative;
    margin: 0 7px;
}
.my_icon_group .my_icon{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.footer_two{
    padding: 55px 0;
}
.my_btn{
    border: none;
    background-color: #706FE5;
    color: white;
    border-radius: 12px;
    padding: 10px 40px;
    margin-top: 50px;
}
.footer_menu h4{
    color: #ccc;
}
ul{
    display: flex;
    justify-content: space-around;
    padding: 0;
    margin-top: 30px;
}
ul li{
    list-style: none;
    margin-right: auto;
}
ul li a{
    text-decoration: none;
    color: #ccc;
}
</style>