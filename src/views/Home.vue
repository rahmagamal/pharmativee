<template>
  <div>
    <Header />
    <div class="content">
     <hooper :itemsToShow="1" :centerMode="true"  :autoPlay="true">
          <slide>
           <img width="100%" src="../assets/pic1.jpg">
          </slide>
          <slide>
            <img width="100%" src="../assets/pic2.jpg">
          </slide>
          <slide>
             <img width="100%" src="../assets/pic3.jpg">
          </slide>
   <hooper-pagination slot="hooper-addons"></hooper-pagination>
 
</hooper>

    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import {
  Hooper,
  Slide,
   Pagination as HooperPagination
  } from 'hooper';
  import 'hooper/dist/hooper.css';
export default {
  name: "Home",
  components: {
    Header,
     Hooper,
    Slide,
    HooperPagination
    
  },
 methods:{

 },
  created(){

  }
}


</script>
<style >
.hooper {
    
    height: fit-content !important;
}
</style>