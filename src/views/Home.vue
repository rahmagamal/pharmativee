<template>
  <div>
    <Header />
    <div class="">
     <hooper :itemsToShow="1" :centerMode="true"  :autoPlay="false">
          <slide class="background">
           <img width="100%" src="../assets/pic22.jpg">
           <div class="contentt">
               <h1 class="title"><strong class="textColor">Pharmative</strong> Opens 24 Hours</h1>
              <h4 class="subTitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit.<br /> Facilis ex perspiciatis non quibusdam vel quidem.</h4>
             <button type="button" class="btn  bttn">Shop Now</button>
           </div>
          
          </slide>
          <slide class="background">
            <img width="100%" src="../assets/pic1.jpg">
           
             <div class="contentt">
               <h1 class="title"> New Medicine <strong class="textColor">Everday</strong> </h1>
              <h4 class="subTitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit.<br /> Facilis ex perspiciatis non quibusdam vel quidem.</h4>
             <button type="button" class="btn  bttn">Shop Now</button>
           </div>
          </slide>
           <slide class="background">
            <img width="100%" src="../assets/pic33.jpg">
           
             <div class="contentt">
               <h1 class="title textColor"> New Medicine <strong class="textColor">Everday</strong> </h1>
              <h4 class="subTitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit.<br /> Facilis ex perspiciatis non quibusdam vel quidem.</h4>
             <button type="button" class="btn  bttn">Shop Now</button>
           </div>
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
.contentt
{
 position: absolute;
  top:30%;
  left: 34%
  
}
.title{
  color: white;
}
.subTitle{

  color: white;
}
.bttn{
    font-size: 25px;
    background-color: white;
    border-color: white;
    color:#75b239;
}
.bttn :hover{
   border-color: #fff !important;
   background-color: red !important;
    color:#75b239 !important;
}
.background{
  position :relative
}
.textColor{
  color: #75b239 ;
}

@media screen and (max-width:763px) {
  .contentt
{
 position: absolute;
  top: 28% !important;
    left: 0% !important;
  
}
}
</style>