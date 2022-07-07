<template>
  <div>
<div class="bg-[#222222] w-full  ">
    
  <div class="home h-max lg:min-h-screen lg:h-screen flex flex-col ">
    <Navbar />
    <MobileNav />


  <!-- ---- -->

  <div class="flex w-full h-full">
    <div class="hidden lg:flex about w-4/12 h-full "></div>


     <div class="w-12/12 lg:w-8/12 h-full flex flex-col  lg:justify-center">
            <div class=" w-full h-auto lg:h-3/6  flex flex-col px-2 lg:px-8 lg:justify-center lg:px-36">
               <h2 class="text-2xl lg:text-6xl font-[avenir-black] font-[750] pb-6 text-white" >About <span class="text-[#F6FF82]">Us</span></h2>
                <p class="text-white text-justify text-sm lg:text-2xl font-[avenir-light]  lg:font-[avenir-black] py-6 lg:py-0">
                  We are  dedicated to giving our users a seamless and total control
of everything regarding their finances, from expenses to earnings 
all controlled from their comfort be it their mobile phones of their 
laptops.
                </p>

            </div>

            <div class=" w-full h-auto lg:h-3/6  flex flex-col px-2 lg:px-8 justify-center bg-[#F6FF82] lg:px-36 ">
                 <p class="text-[#222222] w-full text-justify text-sm lg:text-2xl  font-[avenir-light]  lg:font-[avenir-black] py-6 lg:py-0">
                  We are  dedicated to giving our users a seamless and total control
of everything regarding their finances, from expenses to earnings 
all controlled from their comfort be it their mobile phones of their 
laptops.</p>  
            </div>
     </div>
  </div>

  </div>  


  <!-- ----- -->

   <div class="home min-h-max  flex flex-col  pt-20 lg:items-center ">
     <h2 class="text-2xl lg:text-6xl px-4 lg:px-0 font-[avenir-black] font-[750] pb-6 text-white" >Meet The <span class="text-[#F6FF82]">Team</span></h2>

     <div class="flex flex-col lg:flex-row w-full gap-8  h-max justify-center items-center lg:items-start lg:px-20 pt-12" >

      <div class=" w-10/12 lg:w-4/12 flex flex-col mb-12">
        <div class="flex flex-col gap-4">
          <img src="../assets/person1.jpg">

          <div class="text-white">
            <h2 class="text-xl font-[avenir-black] font-[750] ">Joan Dave</h2>
            <p>CEO</p>
          </div>


            <div class="flex flex-col gap-4 pt-12">
          <img src="../assets/person2.jpg">

          <div class="text-white">
            <h2 class="text-xl font-[avenir-black] font-[750] ">Oba Bobs</h2>
            <p>CTO</p>
          </div>
        </div>

        </div>
      </div>



        <div class="w-10/12 lg:w-4/12 mt-2  lg:mt-20 mb-12">
            <div class="flex flex-col  pt-4 gap-4">
          <img src="../assets/person3.jpg">

          <div class="text-white">
            <h2 class="text-xl font-[avenir-black] font-[750] ">Phillip John</h2>
            <p>Software Engineer</p>
          </div>

      </div>



         <div class="flex flex-col gap-4 pt-12 ">
          <img src="../assets/person4.jpg">

          <div class="text-white">
            <h2 class="text-xl font-[avenir-black] font-[750] ">Grace Justin</h2>
            <p>Senior Desginer</p>
          </div>

      </div>

      </div>

      
    
     </div>

     <!-- ----- -->

     <div class="flex w-full justify-end pr-[10%] lg:pr-[20%] text-white text-sm  lg:text-xl items-center mb-[3rem]">
     <p>Meet the rest of us <span class="text-[#F6FF82] text-2xl">&rarr;</span></p>
     </div> 
   </div>


</div>
<Footer />
  </div>
</template>


<script>
import Navbar from '@/components/Navbar.vue';
import Footer from '@/components/Footer.vue';
import MobileNav from '@/components/MobileNav.vue';


export default {
    components: { Navbar, Footer, MobileNav }
}
</script>


<style scoped>
.about{

  background:url("../assets/about1.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
