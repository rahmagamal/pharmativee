<template>
  <div class="pharmative">
    <Header />
      <!------------section 1------------->
    <div id="home">
    
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
            <img class="pic" width="100%" src="../assets/pic8.jpg">
           
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
    <div class="container mt-5" id="about">
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

    <!----section3 ---------->
    <div class="container mt-5 p3 mb-5" id="products">
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
                   <img class="productimg" src="../assets/product1.png">
                   <h3>Umcka Cold Care</h3>
                   <p>12.00$</p>
            </div>
          </slide>
           <slide>
            <div class="product">
                   <img class="productimg" src="../assets/product3.jpg">
                    <h3>Get Clear Skin</h3>
                   <p>25.00$</p>
            </div>
          </slide>
           <slide>
            <div class="product">
                   <img class="productimg" src="../assets/product4.jpg">
                    <h3>Get Clear Skin</h3>
                   <p>25.00$</p>
            </div>
          </slide>
           <slide>
            <div class="product">
                   <img class="productimg" src="../assets/product5.jpg">
                    <h3>Get Clear Skin</h3>
                   <p>25.00$</p>
            </div>
          </slide>
           <slide>
            <div class="product">
                   <img class="productimg" src="../assets/product6.jpg">
                    <h3>Umcka Cold Care</h3>
                   <p>12.00$</p>
            </div>
          </slide>
  <hooper-navigation slot="hooper-addons"></hooper-navigation>
</hooper>
      </div>
    </div>

    <!------------section 4  ------------>
    <div class="signUp mt-5 mb-5  ">
      
        <div class="container">
            <div class="row justify-content-center text-center">
              <div class="col-md-7">
                <h3 class="coverText">
                  Sign up for discount up to 55% OFF
                </h3>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo omnis voluptatem consectetur quam.</p>
             <button type="button" class="btn  coverBtn">Sign Up</button>
             
              </div>
            </div>
       </div>
         
        
     
     
    </div>

    <!----- section 5--------------------->
    <div class="container-fluid mb-5" id="whyUs">
      <div class="row customerTitle">
        <div class="col-md-6">
          
          <h1>Happy <span class="textColor"> Customers</span></h1>
           <svg height="50">
          <line x1="0" y1="0" x2="70" y2="0" style="stroke:#75b239;stroke-width:10" />
        </svg>
          <hooper :itemsToShow="1" :centerMode="true" :autoPlay="true" >
          <slide >
            <div class="col-md-12 mb-2">
                  <img class="customerPic" src="../assets/pic5.jpg">
            </div>
         
           <div class="col-md-10">
             <p>
               “Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo omnis voluptatem consectetur quam tempore
                  obcaecati maiores voluptate aspernatur iusto eveniet, placeat ab quod tenetur ducimus. Minus ratione sit quaerat
                  unde.”
             </p>
              <p class="textColor">— Rebecca Morando</p>
           </div>
          
          </slide>
           <slide >
            <div class="col-md-12 mb-2">
                  <img class="customerPic" src="../assets/pic6.jpg">
            </div>
         
           <div class="col-md-10">
             <p>
               “Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo omnis voluptatem consectetur quam tempore
                  obcaecati maiores voluptate aspernatur iusto eveniet, placeat ab quod tenetur ducimus. Minus ratione sit quaerat
                  unde.”
             </p>
              <p class="textColor">—Andrew Neel</p>
           </div>
          
          </slide>
          <slide >
            <div class="col-md-12 mb-2">
                  <img class="customerPic" src="../assets/pic7.jpg">
            </div>
         
           <div class="col-md-10">
             <p>
               “Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo omnis voluptatem consectetur quam tempore
                  obcaecati maiores voluptate aspernatur iusto eveniet, placeat ab quod tenetur ducimus. Minus ratione sit quaerat
                  unde.”
             </p>
              <p class="textColor">—Mai Neel</p>
           </div>
          
          </slide>
        
          
      <hooper-pagination slot="hooper-addons"></hooper-pagination>
    
        </hooper>

        </div>
        <div class="col-md-6">
          <h1>Why <span class="textColor"> Us</span></h1>
          <svg height="50">
            <line x1="0" y1="0" x2="70" y2="0" style="stroke:#75b239;stroke-width:10" />  
        </svg>
        <div class="row mb-2">
          <div class="col-md-2">
            <div class="dot">
              <p class="dotNum">1</p>
            </div>
          </div>
          <div class="col-md-8">
            <p>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo omnis voluptatem consectetur quam tempore
            </p>
          </div>
        </div>
        <div class="row mb-2">
          <div class="col-md-2">
            <div class="dot">
              <p class="dotNum">2</p>
            </div>
          </div>
          <div class="col-md-8">
            <p>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo omnis voluptatem consectetur quam tempore
            </p>
          </div>
        </div>
        <div class="row">
          <div class="col-md-2">
            <div class="dot">
              <p class="dotNum">3</p>
            </div>
          </div>
          <div class="col-md-8">
            <p>
              Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nemo omnis voluptatem consectetur quam tempore
            </p>
          </div>
        </div>
        </div>
      </div>
    </div>


    <!-------Footer ------->
    <footer class="foter">
      <div class="container-fluid">
      <div class="row">
        <div class="col-md-3 mt-5 ">
          <ul>
          <h3>About <span class="textColor"> Pharmative</span></h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
             Eius quae reiciendis distinctio voluptates sed dolorum excepturi iure eaque, aut unde.</p>
      </ul>
        </div>
        <div class="col-md-3 offset-md-1 mt-5 ">
          
          <ul>
            <h3 class="textColor">Navigation</h3>
            <li>Supplements</li>
            <li>Vitamins</li>
            <li>Diet & Nutrition</li>
            <li>Tea & Coffee</li>

          </ul>
        </div>
        <div class="col-md-3 offset-md-1 mt-5 ">
           
            <ul>
              <h3 class="textColor">Contact Info</h3>
            <li class="mb-2">
              <span>
                <i class=" mr-2 fas fa-map-marker-alt"></i>
              </span>
              Cairo,Egypt</li>
            <li class="mb-2">
              <span>
                <i class=" mr-2 fas fa-phone-alt"></i>
              </span>
              0105669732</li>
            <li class="mb-2">
              <span><i class=" mr-2 fas fa-envelope"></i></span>
              pharmative@gmail.com</li>
            

          </ul>
        </div>

      </div>
      <div class="col-md-12 text-center mt-5">
      <p> Copyright © 2020 All rights reserved |  made with Love by RahmaGamal </p>
      </div>
      </div>
    </footer>
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
   /* min-height: 500px !important; */
   background-size: cover;
   height: 93vh;
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
.productimg{
  height: 400px;
  width: 70%;
}

/*section 4 *****************/


.signUp{
  width: 100%;
  height: 300px;
  /* background-image: url("../assets/pic3.jpg");
  background-repeat: no-repeat;
  background-size: cover; */
  background-color: #75b239;
  color: white;
}
.coverText{
 margin-top: 15%;
}
.coverBtn{
      font-size: 21px;
    background-color: #f5eeee08;
    border-color: white;
    color: #ffffff;
}
.coverBtn:hover{
  color: #75b239 !important;
    background-color: white !important;
}


/* section 5 */

.customerTitle{
  text-align: left;
}
.customerPic{

  border-radius: 50%;
  width: 80px;
  height: 80px;
}
.dot{
  height: 80px;
  width: 80px;
  background-color: #75b239;
  border-radius: 50%;
  display: inline-block;
  position: relative;
}
.dotNum{
  position: absolute;
  top: 27%;
    left: 40%;
    font-size: 26px;
  color: white;
}

/*footer  */
.foter{
  background-color: #f5f6f7 ;
  text-align:left;
}
.foter ul{
  list-style: none;
  font-size: 20px;
}
.foter i{
  font-size: 26px;
  color: #75b239;
}
@media screen and (max-width:763px) {
  .contentt
{
    position: absolute;
    top: 24% !important;
    left: 0% !important;
  
}
.product{
  height: 300px;
}
.productimg{
  height: 55%;
 
}
.pic{
  min-height: 600px;
  height: 70vh !important;
}
.subTitle{
font-size: 18px;
}
}
.hooper-indicator.is-active {
    background-color: #75b239 !important;
}
</style>