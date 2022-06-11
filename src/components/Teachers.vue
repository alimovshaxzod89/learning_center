<template>
    <div class="content mt-5">
        <component :is="selectedComp"></component>
        <div class="container d-flex flex-wrap justify-content-center mt-5">

            <div class="teacher_cards" @click="selectedComp='AboutTeacher1'">
                <div class="teacher_photo d-flex justify-content-center">
                    <img src="@/assets/img/teacher1.png" alt="">
                </div>
                <h4>Adam Smith</h4>
                <p>Math</p>
            </div>

            <div class="teacher_cards" @click="selectedComp='AboutTeacher2'">
                <div class="teacher_photo d-flex justify-content-center">
                    <img src="@/assets/img/teacher2.png" alt="">
                </div>
                <h4>William Joze</h4>
                <p>Philosofy</p>
            </div>

            <div class="teacher_cards" @click="selectedComp='AboutTeacher3'">
                <div class="teacher_photo d-flex justify-content-center">
                    <img src="@/assets/img/teacher3.png" alt="">
                </div>
                <h4>Samuel Umtiti</h4>
                <p>Music</p>
            </div>
            
            <div class="teacher_cards" @click="selectedComp='AboutTeacher4'">
                <div class="teacher_photo d-flex justify-content-center">
                    <img src="@/assets/img/teacher4.png" alt="">
                </div>
                <h4>Dr.Martin</h4>
                <p>Anothomy</p>
            </div>
        </div>
    </div>
</template>
<script>
import AboutTeacher1 from '@/components/Teachers/AboutTeacher1.vue'
import AboutTeacher2 from '@/components/Teachers/AboutTeacher2.vue'
import AboutTeacher3 from '@/components/Teachers/AboutTeacher3.vue'
import AboutTeacher4 from '@/components/Teachers/AboutTeacher4.vue'
export default {
    data(){
    return{
        selectedComp:'AboutTeacher1'
    }
    },
    components:{
        AboutTeacher1,
        AboutTeacher2,
        AboutTeacher3,
        AboutTeacher4
    }
}
</script>
<style scoped>
.content{
    background-color: rgba(112, 111, 229, 0.02);
}
.teacher_cards{
    padding: 0 20px;
}
.teacher_photo img{
    width: 60px;
    height: 60px;
    border-radius: 50%;
    border: .8px solid rgba(0, 0, 0, 0.404);
}
h4{
    font-family: 'Poppins', sans-serif;
    font-weight: 700;
    font-size: 24px;
    line-height: 36px;
    text-align: center;
}
p{
    font-weight: 400;
    font-size: 20px;
    line-height: 30px;
    text-align: center;
}
</style>