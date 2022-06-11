<template>
    <div>
        <div class="about_us container d-flex justify-content-between">
            <!-- Left -->
            <div class="left w-50">
                <h1>How we can help you</h1>
                <p>Follow our newsletter. We will regulary update <br> our latest project and availability.</p>
                <div>
                    <textarea name="" id="" cols="40" rows="5" placeholder="Send to your menssage"></textarea>
                </div>
                <button class="my_btn">Send to message</button>
            </div>
            
            <!-- Right -->
            <div class="right w-50">
                <div class="right_top d-flex justify-content-between">
                    <div>
                        <div class="my_icon_group">
                            <box-icon class="my_icon" name='bar-chart-alt-2' color='white' ></box-icon>
                        </div>
                        <h3>UI/UX Design</h3>
                        <p>Sometimes features require <br> a short description</p>
                    </div>
                    <div>
                        <div class="my_icon_group">
                            <box-icon class="my_icon" type='solid' name='barcode' color='white'></box-icon>
                        </div>
                        <h3>UI/UX Design</h3>
                        <p>Sometimes features require <br> a short description</p>
                    </div>
                </div>
                <div class="right_bottom d-flex justify-content-between">
                    <div>
                        <div class="my_icon_group">
                            <box-icon class="my_icon" type='solid' name='barcode' color='white'></box-icon>
                        </div>
                        <h3>UI/UX Design</h3>
                        <p>Sometimes features require <br> a short description</p>
                    </div>
                    <div>
                        <div class="my_icon_group">
                            <box-icon class="my_icon" type='solid' name='barcode' color='white'></box-icon>
                        </div>
                        <h3>UI/UX Design</h3>
                        <p>Sometimes features require <br> a short description</p>
                    </div>
                </div>
            </div>
        </div>
        
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.about_us{
    margin-top: 15%;
}
.left h1{
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
    font-size: 40px;
    font-weight: 52px;
    letter-spacing: .2px;
}
.left p{
    font-family: 'Poppins', sans-serif;
    font-weight: 400;
    font-size: 20px;
    line-height: 36px;
    color: #2E3E5C;

}
.my_icon_group{
    width: 70px;
    height: 70px;
    background-color: #706FE5;
    color: white;
    border-radius: 50%;
    position: relative;
}
.my_icon_group .my_icon{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
.right h3{
    font-family: 'Poppins', sans-serif;
    font-weight: 600;
    font-size: 20px;
    line-height: 28px;
    margin: 10px 0;
}
.right p{
    font-family: 'Poppins', sans-serif;
    font-size: 16px;
    line-height: 28px;
    color: #2E3E5C;
}
.my_btn{
    border: none;
    background-color: #706FE5;
    color: white;
    border-radius: 12px;
    padding: 10px 40px;
    margin-top: 10px;
}
</style>