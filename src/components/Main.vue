<template>
    <div>
        <Statistics />
        <VueHooper />
        <Teachers />
    </div>
</template>
<script>
import Statistics from '@/components/Statistics.vue'
import VueHooper from '@/components/Vue_hoopers.vue'
import Teachers from '@/components/Teachers.vue'
export default {
    components:{
        Statistics,
        VueHooper,
        Teachers
    }
}
</script>
<style scoped>

</style>