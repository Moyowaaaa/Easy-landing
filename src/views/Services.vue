<template>
    <div>
        <div class="bg-[#222222] w-full  ">
              <div class="home h-auto min-h-screen flex flex-col ">
            <Navbar />
            <MobileNav />

            <div class="h-[10rem] px-4 lg:h-[20rem]  flex flex-col justify-center lg:px-20 bg-[#F6FF82]">
                <h2 class="text-3xl lg:text-6xl font-[avenir-black] font-[750] pb-6 text-[#222222]" >Services</h2>



              
            </div>
                    <div class=" mt-[-5vh] lg:absolute lg:mt-0  w-11/12 h-auto lg:h-[20rem] top-[20rem] left-20 lg:flex flex-col lg:flex-row   lg:justify-evenly gap-12 mx-auto lg:mx-0">
                <div class="h-5/6 lg:h-full w-10/12 lg:w-4/12  mb-4 lg:mb-0  bg-white rounded-md flex flex-col gap-4 justify-center px-4 shadow-md mx-auto" >
                    <h2 class="text-2xl lg:text-3xl font-[avenir-black] font-[750] pt-6 lg:pt-0">Total Control </h2>
                    <p class="text-justify pb-6 lg:pb-0">
                        We give you the ability to manage your 
finances via any platform of choice from 
large desktop screens to laptops to your 
tablets and phone.
All your data is synced and available at 
anytime.
                    </p>
                </div>

                <div class="h-5/6 lg:h-full w-10/12 lg:w-4/12  mb-4 lg:mb-0 bg-white rounded-md flex flex-col gap-4 justify-center px-4 shadow-md mx-auto">
                    <h2 class="text-2xl lg:text-3xl font-[avenir-black] font-[750] pt-6 lg:pt-0">Security</h2>
                    <p class="text-justify pb-6 lg:pb-0">
                        We give you the ability to manage your 
finances via any platform of choice from 
large desktop screens to laptops to your 
tablets and phone.
All your data is synced and available at 
anytime.
                    </p>
                </div>


                <div class="h-auto lg:h-full w-10/12 lg:w-4/12  mb-4 lg:mb-0 bg-white rounded-md flex flex-col gap-4 justify-center px-4 shadow-md mx-auto">
                    <h2 class="text-2xl lg:text-3xl font-[avenir-black] font-[750] pt-6 lg:pt-0">Cross Platform </h2>
                    <p class="text-justify pb-6 lg:pb-0">
                        We give you the ability to manage your 
finances via any platform of choice from 
large desktop screens to laptops to your 
tablets and phone.
All your data is synced and available at 
anytime.
                    </p>
                </div>

                </div>

            <!-- <ServiceCards /> -->

        

         

            <div class="hidden h-4/6 mt-[20rem]  lg:flex flex-col justify-center px-20 bg-[#222222]">

             <div class="flex w-full items-center h-[20rem]  bg-[#F6FF82] rounded-md">
                <div class="h-3/6 w-4/12 border-r-4 border-r-[#222222] flex flex-col justify-center items-center">
                    <h2 class="text-6xl font-[avenir-black] font-[750]">3000+</h2>
                    <p class="text-xl font-[avenir-black] ">Downloads</p>
                </div>

                 <div class="h-3/6 w-4/12 border-r-4 border-r-[#222222] flex flex-col justify-center items-center ">
                    <h2 class="text-6xl font-[avenir-black] font-[750]">3000+</h2>
                    <p class="text-xl font-[avenir-black] ">Downloads</p>
                </div>

                 <div class="h-3/6 w-4/12  flex flex-col justify-center items-center">
                    <h2 class="text-6xl font-[avenir-black] font-[750]">4</h2>
                    <p class="text-xl font-[avenir-black] ">Awards</p>
                </div>

             </div>  
            </div>


            <div class="w-11/12 mx-auto h-screen lg:hidden flex flex-col gap-2 my-12">
                <div class="h-2/6  rounded-md  bg-[#F6FF82] flex flex-col justify-center items-center">
                      <h2 class="text-6xl font-[avenir-black] font-[750]">3000+</h2>
                    <p class="text-xl font-[avenir-black] ">Downloads</p>
                </div>

                   <div class="h-2/6  rounded-md  bg-[#F6FF82] flex flex-col justify-center items-center">
                      <h2 class="text-6xl font-[avenir-black] font-[750]">3000+</h2>
                    <p class="text-xl font-[avenir-black] ">Downloads</p>
                </div>

                  <div class="h-2/6  rounded-md  bg-[#F6FF82] flex flex-col justify-center items-center">
                      <h2 class="text-6xl font-[avenir-black] font-[750]">4</h2>
                    <p class="text-xl font-[avenir-black] ">Awards</p>
                </div>
            </div>



            </div>  

        </div>
        <Footer />
    </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';
import ServiceCards from '../components/ServiceCards.vue';
import Footer from '@/components/Footer.vue';
import MobileNav from '@/components/MobileNav.vue';





export default {
    components: { Navbar, ServiceCards, Footer, MobileNav }
}
</script>