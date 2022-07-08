<template>
<div class="">

  <div class="bg-[#222222] w-full ">
    <Navbar/> 
    <MobileNav />


     <div class="home min-h-screen justify-center flex flex-col  lg:px-20  ">
    <div class="flex flex-col-reverse lg:flex-row justify-between w-full px-[1rem]">

      <div class="w-full lg:w-7/12  flex flex-col text-white justify-center gap-4 pt-[1.5rem] lg:pt-0">

        
        <div class="flex flex-col items-center  lg:items-start">
        <h2 class="text-2xl lg:text-6xl font-[avenir-black] font-[750] text-center lg:text-left" >Managing your finances</h2>
        <h2 class="text-2xl lg:text-6xl font-[avenir-black] font-[750] text-center lg:text-left">has never been this easy.</h2>
        <p class="text-center lg:text-left">All your expenses and expected income all in one place.</p>


        <div>
        <button class="flex mt-[2rem] font-[avenir-black] py-4 px-10 bg-[#F6FF82] gap-4 items-center text-black">Get Started
          <img src="../assets/forwardarrow.svg" />


        </button>
      </div>
      </div>  
  

      </div>

      

    <div class="w-11/12 lg:w-5/12 flex flex-col items-center mx-auto lg:mx-0">
      <img src="../assets/homecard.svg">
      <img src="../assets/emoticons.svg" class="lg:mt-[-10vh]">
    </div>


      
      </div>  
      </div>  

       <div class="home lg:min-h-screen  flex flex-col items-center justify-center lg:px-20 lg:flex-row">
        <div class="w-11/12  lg:w-7/12 text-2xl lg:text-6xl flex  font-[avenir-black] text-white">
          <h2>Expenses and Profit all in one <span class="text-[#F6FF82]">place</span></h2>
        </div>

        <div class="w-9/12 lg:w-5/12 flex flex-col pt-12  ">
          <img src="../assets/card.svg" />
        </div>

       </div>


       <div class="home min-h-screen  flex flex-col justify-center gap-6 lg:px-20">
            <div class="w-full text-2xl lg:text-7xl flex font-[avenir-black] text-white pl-4 lg:pl-0">
          <h2><span class="text-[#F6FF82] ">Trusted</span> by 3000+ businesses</h2>
        </div>

        <div class="text-white w-full lg:w-4/12">
          <p class="text-xs lg:text-base px-2 lg:px-0 pl-4 lg:pl-0">From small, medium and large, different companies of different sizes 
trust us to when managing and secure their finances.</p>
        </div>

        <div class="w-9/12 lg:w-full mx-auto lg:mx-0 flex flex-col lg:flex-row gap-2 justify-center gap-4 lg:gap-8 ">
          <img src="../assets/rectangle1.svg" />
          <img src="../assets/rectangle2.svg" />

        </div>

       </div>


     
       </div> 


       <div class="h-auto lg:h-[60vh] flex flex-col">

        <div class="w-full lg:px-20 bg-[#F6FF82]  h-full flex flex-col lg:flex-row items-center justify-center ">

          <div class=" w-full text-center lg:text-left lg:w-7/12 text-2xl lg:text-6xl text-black flex font-[avenir-black] text-white pt-6 pb-12 lg:pt-0 lg:pb-0">
          <h2> All payment managed in one app</h2>
        </div>


          <div class="pb-6">
            <img src="../assets/transactions.svg" />
          </div>
         </div>
       </div>
       <!-- ---- -->

       <div class="lg:min-h-screen flex flex-col lg:px-20 bg-[#222222] gap-4 pb-24 justify-around pt-12 lg:pt-0">
  <h1 class="text-2xl lg:text-6xl text-[#F6FF82] flex font-[avenir-black]">
            Testimonies
          </h1>


         
        <div class=" lg:px-20 flex flex-col flex-wrap w-full h-auto pt-4 items-center justify-center overflow-x-scroll pb-4" id="overflow">
        

          <div class="flex flex-row gap-4 lg:gap-8 ">

            <div class="bg-white w-[20rem] lg:w-[30rem] justify-center items-center flex flex-col  rounded-md h-[12rem] lg:h-[18rem]">

              <div class="flex w-10/12 items-center gap-2 lg:w-11/12 justify-center ">
                <img src="../assets/user1.svg">
                <div class="flex flex-col">
                  <p class="font-[avenir-black] text-black">John Stewart <span class="font-[avenir-light]"><small>Fitness Trainer</small></span></p>
                  <p>
                    Easy...well makes monitoring finances easy. All income 
and expenses are easy to monitor. 
                  </p>
                </div>
              </div>

            </div>


            <div class="bg-white w-[20rem] lg:w-[30rem] justify-center items-center flex flex-col  rounded-md h-[12rem] lg:h-[18rem]">
              <div class="flex items-center gap-2 w-11/12 justify-center ">
                <img src="../assets/user2.svg">
                <div class="flex flex-col">
                  <p class="font-[avenir-black] text-black">Suzan John <span class="font-[avenir-light]"><small>Teacher</small></span></p>
                  <p>
                    Easy...well makes monitoring finances easy. All income 
and expenses are easy to monitor. 
                  </p>
                </div>
              </div>

            </div>

             <div class="bg-white w-[20rem] lg:w-[30rem] justify-center items-center flex flex-col  rounded-md h-[12rem] lg:h-[18rem]">
              <div class="flex items-center gap-2 w-11/12 justify-center ">
                <img src="../assets/user3.svg">
                <div class="flex flex-col">
                  <p class="font-[avenir-black] text-black">John Gift <span class="font-[avenir-light]"><small>Accountant</small></span></p>
                  <p>
                    Easy...well makes monitoring finances easy. All income 
and expenses are easy to monitor. 
                  </p>
                </div>
              </div>

            </div>
            </div>  
            





            <!-- <img src="../assets/testimony1.svg" />
            <img src="../assets/testimony2.svg" />
            <img src="../assets/testimony3.svg" /> -->
          </div>



        </div>








    <Footer />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

import Footer from '../components/Footer.vue'
import MobileNav from '@/components/MobileNav.vue';

export default {
  name: "HomeView",
  components: {
    Navbar,
    Footer,
    MobileNav
},
 
};
</script>


<style>
#overflow::-webkit-scrollbar{
  width: 5px;
  height:5px;
  margin-top:2%;
}

#overflow::-webkit-scrollbar-thumb {
  background: #F6FF87;
}
#overflow::-webkit-scrollbar-track {
  background: #222222;
}

</style>
