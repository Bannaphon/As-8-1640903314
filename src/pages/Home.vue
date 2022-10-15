<template>
  <navbar />
  <section class="home">

    <div class="image">
        <img src="images/day6-.png" alt="">
    </div>

    <div class="content">
        <h3>hi, {{name}}</h3>
        <span>{{motto}}</span>
        <p>{{content}}</p>
        <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
    </div>

</section>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },
  data() {
      return {
        name: 'Day 6',
        motto: 'เป็นวงดนตรีจากค่าย JYP Entertainment ปัจจุบันมีสมาชิกทั้งหมด 5 คน คือ เจ (🐥) , ซองจิน (🐻) , ยองเค (🦊) , วอนพิล (🐰) , โดอุน (🐶)',
        content: 'We Are My Day',
      }
 }

}
</script>

<style>

</style>