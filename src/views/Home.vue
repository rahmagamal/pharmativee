<template>
  <div class="pharmative">
    <Header />
      <!------------section 1------------->
    <div>
    
     <hooper :itemsToShow="1" :centerMode="true"  :autoPlay="true">
          <slide class="background">
           <img class="pic" width="100%" src="../assets/pic22.jpg">
           <div class="contentt">
               <h1 class="title"><strong class="textColor">Pharmative</strong> Opens 24 Hours</h1>
              <h4 class="subTitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit.<br /> Facilis ex perspiciatis non quibusdam vel quidem.</h4>
             <button type="button" class="btn  bttn">Shop Now</button>
           </div>
          
          </slide>
          <slide class="background">
            <img class="pic" width="100%" src="../assets/pic1.jpg">
           
             <div class="contentt">
               <h1 class="title"> New Medicine <strong class="textColor">Everday</strong> </h1>
              <h4 class="subTitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit.<br /> Facilis ex perspiciatis non quibusdam vel quidem.</h4>
             <button type="button" class="btn  bttn">Shop Now</button>
           </div>
          </slide>
           <slide class="background">
            <img class="pic" width="100%" src="../assets/pic4.jpg">
           
             <div class="contentt">
               <h1 class="title "> New Medicine <strong class="textColor">Everday</strong> </h1>
              <h4 class="subTitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit.<br /> Facilis ex perspiciatis non quibusdam vel quidem.</h4>
             <button type="button" class="btn  bttn">Shop Now</button>
           </div>
          </slide>
   <hooper-pagination slot="hooper-addons"></hooper-pagination>
 
</hooper>

    </div>
    <!---------section 2------------->
    <div class="container mt-5">
      <div class="row">
        <div class="col-md-4 box mb-3">
            <i class="fas fa-truck-loading mb-3"></i>
            <h4>
              <a href="#"  class="">Free Delivery</a>
            </h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa laborum voluptates excepturi neque labore .</p>
            <a href="#">Learn more <i class="fas fa-angle-right arrow"></i></a>
        </div>
        <div class="col-md-4 box mb-3">
            
            <i class="fas fa-capsules mb-3"></i>
            <h4>
              <a href="#"  class="">New Medicine Everyday</a>
            </h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa laborum voluptates excepturi neque labore .</p>
            <a href="#">Learn more <i class="fas fa-angle-right arrow"></i></a>
        </div>
        <div class="col-md-4 box mb-3">
           
            <i class="fas fa-prescription-bottle-alt mb-3"></i>
            <h4>
              <a href="#"  class="">Medicines Guaranteed</a>
            </h4>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa laborum voluptates excepturi neque labore .</p>
            <a href="#">Learn more <i class="fas fa-angle-right arrow"></i></a>
        </div>
      </div>
    </div>

    <!----products ---------->
    <div class="container mt-5 p3 mb-5">
      <div class="col-md-12">
        <h1>
          Pharmacy <span class="textcolor">Products</span>
        </h1>
        <svg height="50">
          <line x1="100" y1="0" x2="200" y2="0" style="stroke:#75b239;stroke-width:10" />
          
        </svg>

      </div>
      <div class="row">
       <hooper :itemsToShow="3" :infiniteScroll="true" :autoPlay="true">
          <slide>
            <div class="product">
                   <img height="400px" width="70%" src="../assets/product1.png">
                   <h3>Umcka Cold Care</h3>
                   <p>12.00$</p>
            </div>
          </slide>
           <slide>
            <div class="product">
                   <img height="400px" width="70%" src="../assets/product3.jpg">
                    <h3>Get Clear Skin</h3>
                   <p>25.00$</p>
            </div>
          </slide>
           <slide>
            <div class="product">
                   <img height="400px" width="70%" src="../assets/product4.jpg">
                    <h3>Get Clear Skin</h3>
                   <p>25.00$</p>
            </div>
          </slide>
           <slide>
            <div class="product">
                   <img height="400px" width="70%" src="../assets/product5.jpg">
                    <h3>Get Clear Skin</h3>
                   <p>25.00$</p>
            </div>
          </slide>
           <slide>
            <div class="product">
                   <img height="400px" width="70%" src="../assets/product6.jpg">
                    <h3>Umcka Cold Care</h3>
                   <p>12.00$</p>
            </div>
          </slide>
  <hooper-navigation slot="hooper-addons"></hooper-navigation>
</hooper>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import {
  Hooper,
  Slide,
   Pagination as HooperPagination,
    Navigation as HooperNavigation
  } from 'hooper';
  import 'hooper/dist/hooper.css';
export default {
  name: "Home",
  components: {
    Header,
     Hooper,
    Slide,
    HooperPagination,
    HooperNavigation
    
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
.pic{
   min-height: 600px;
}
/*** section 2 */
.box{
  text-align: left;
}
.box a {
  color:#75b239;
  text-decoration: none;
 
}

.box a:hover {
  color:#75b239;
  text-decoration: none;
 
}
.box p{
  color:gray;
}
.box i{
  font-size: 45px;
  color:#75b239
}
.arrow{
  font-size: 14px !important;
}

/***products */

.product{
  background-color: #f7f7f7;
  /* height: 400px; */
    border-radius: 10px;
    padding: 11%;
    margin-right: 2%;
}
@media screen and (max-width:763px) {
  .contentt
{
    position: absolute;
    top: 24% !important;
    left: 0% !important;
  
}
.pic{
  min-height: 600px;
  height: 70vh !important;
}
.subTitle{
font-size: 18px;
}
}
</style>