<template>
  <div>
    
      <nav class="navbar">
         <div class="container">
             <div class="row content">
                   
                 <div class="col-md-3">
                   <span class="text">PHARMA<span class="text2">TIVE</span> </span>
                   <!--- responsive menu --->
              
                       <i class="fas fa-bars  menu " id="menu" @click="clickMenu()"></i>
                      
                 </div>
                  <div v-if="mobile" class="mobileMenu">
                       <ul class=" ">
                         <li class="menuList" @click="clickMenu" > <a href="#home" >HOME  </a>
                         </li>
                          
                         <li class="menuList" @click="clickMenu" > <a href="#about"> About </a></li>
                         <li class="menuList" @click="clickMenu" > <a href="#products"> Products </a></li>
                         <li class="menuList" @click="clickMenu" > <a href="#whyUs"> WHY US </a></li>
                         
                         <!-- <li class="menuList" @click="clickMenu" > <a href="#contact"> CONTACT US</a></li> -->


                     </ul>
                      </div>
                 <div class="col-md-6">
                   
                     <ul >
                         <li class="list "> <a href="#" class="textcolor"> Home  </a>
                         </li>
                          <!-- <svg height="1" width="20">
                            <line x1="0" y1="0" x2="50" y2="0" style="stroke:#75b239;stroke-width:2" />
                          </svg> -->
                         <li class="list"> <a href="#about"> About </a></li>
                         <li class="list"> <a href="#products"> Products </a></li>
                         <li class="list"> <a href="#whyUs"> Why Us </a></li>
                         <!-- <li class="list"> <a href="#contact"> Contact </a></li> -->

                     </ul>
                    
                 </div>
                 <div class="col-md-3 textfont">
                    
                      <i class="fas fa-search mr-2 icon"></i>
                      <i class="fas fa-shopping-cart icon"></i>
                      <svg height="10" width="20">
                        <circle cx="30" cy="30" r="10" stroke="#75b239" stroke-width="3" fill="#75b239" />
                      </svg>
                   
                 </div>
             </div>

             
         
         </div>
      
      </nav>
      
  </div>
</template>

<script>
export default {
   data(){
      return{
         mobile:false
      }
  },
        methods:{
      clickMenu(){
          this.mobile=!this.mobile
      }
  }

}
</script>

<style>
* {box-sizing: border-box;}
body { 
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}
.navbar{
    width: 100%;
    height: 80px;
    background-color:white;
    position: fixed;
    top:0;
    z-index:9999;
    padding: 2%;
    box-shadow: 0px 10px #f9f9f9;
}
.content{
  width: 100% !important ;
}
.list {

    display: inline-block;
    text-decoration: none;
    color: #25262a;
   margin-right: 30px;
    font-size: 18px;

}
.list a{
   text-decoration: none;
    color: #25262a;
}
.list a:hover {
  
    color: #75b239 !important;
}

.text{
  font-size: 20px;
    font-weight: 600;
    color: #75b239 !important;
}
.text2{
  font-size: 20px;
    font-weight: 600;
    color: black;
}
.textcolor{
  color: #75b239 !important;
}
.textfont{
  font-size: 20px;
}
.menu{
  display: none !important;
}
.mobileMenu{
     display: unset;
    margin-left: 34px;
    background-color: #f5f5f5;
    opacity: 0.7;
    width: 100%;
    line-height: 3.2;
    margin-top: 9%;
}
 .mobileMenu   li{
    
      list-style-type: none;
      
    }
    .mobileMenu a{
      color: #75b239 !important;
    }
  .mobileMenu  .menuList{
      margin-left: -20%;
      
    }

@media only screen and (max-width:763px){
  .list a{
    display:none
  }
  .icon{
    display:none
  }
  .navbar{
    height: 60px;
  }
  .text{
    display: block;
    float:left;
    font-size: 23px;
  }
  .text2{
  
    font-size: 23px;
  }
  .menu{
  display: unset !important;
  float: right;
  font-size: 23px;
  margin-top: 5px;
  color: #75b239 !important;
}
  
}
</style>