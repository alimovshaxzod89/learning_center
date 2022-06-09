<template>
  <div class="container mt-5">
    <div>
      <h3 class="title mb-4">We create world-class digital classes</h3>
    </div>
    <div class="row" >
      <div class="col-md-12" >
        <hooper :progress="true" :autoPlay="true" :playSpeed="3000" style="height: 450px;">
          <slide >
            <img class="w-50" src="@/assets/img/lCenter1.jpg" alt="">
            <img class="w-50" src="@/assets/img/lCenter1.jpg" alt="">
          </slide>
          <slide>
            <img class="w-50" src="@/assets/img/lCenter2.jpg" alt="">
            <img class="w-50" src="@/assets/img/lCenter2.jpg" alt="">
          </slide>
          <slide>
            <img class="w-50" src="@/assets/img/lCenter3.jpg" alt="">
            <img class="w-50" src="@/assets/img/lCenter3.jpg" alt="">
          </slide>
          <slide>
            <img class="w-50" src="@/assets/img/lCenter4.jpg" alt="">
            <img class="w-50" src="@/assets/img/lCenter4.jpg" alt="">
          </slide>
          <slide>
            <img class="w-50" src="@/assets/img/lCenter5.jpg" alt="">
            <img class="w-50" src="@/assets/img/lCenter5.jpg" alt="">
          </slide>
          <slide>
            <img class="w-50" src="@/assets/img/lCenter6.jpg" alt="">
            <img class="w-50" src="@/assets/img/lCenter6.jpg" alt="">
          </slide>
        </hooper>
      </div>
    </div>
  </div>
</template>

<script>
import {
  Hooper,
  Slide,
} from 'hooper';
import 'hooper/dist/hooper.css';

export default {
  name: 'App',
  components: {
    Hooper,
    Slide,
  },
  data() {
    return {
    }
  }
};
</script>

<style scoped>
img{
  border-radius: 10px;
  padding: 5px;
}
h3{
  font-family: 'Poppins', sans-serif;
  font-size: 40px;
  font-weight: 700;
  line-height: 52px;
  letter-spacing: 0.2px;
}
</style>