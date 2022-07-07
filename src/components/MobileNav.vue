<template>
    <div class="block lg:hidden py-10 ">

        <div class="w-full flex justify-between items-center">
              <router-link to="/">
            <h1 class="font-[avenir-black] font-[750] text-white pl-4">Easy</h1>
            </router-link>


    

            <div class="absolute  right-0 pr-4"   @click="toggle">
                <img src="../assets/kebab.svg" :class="[open ? 'hidden' : 'flex']">

                <p class="text-white text-xl " :class="[open ? 'flex' : 'hidden']">X</p>

            </div>


            <div class="absolute bg-[#222222] w-full duration-200 ease-in text-[avenir-light] pl-4" :class="[open ? 'top-20' : 'top-[-100%]']">
              <div class="flex flex-col gap-4 border-t-2 border-t-[#F6FF82] pt-4 pb-4">
                <router-link to="/about">
                <p class="text-white">About</p>
                </router-link>
                <router-link to="/services">
                <p class=" text-white">Services</p>
                </router-link>
                <p class=" text-white">Download</p>
                <router-link to="/signup">
                <div>
                <button class=" w-11/12 mx-auto p-4 px-12 bg-[#F6FF82] font-[750] text-black flex items-center justify-center font-[avenir-black] font-bold">
                    Sign Up
                </button>
                </div>
                </router-link>
              </div>
            </div>

            
        </div>

      
    </div>
</template>


<script>
const { ref }=require("vue")


export default {
    name: "Navbar",
    components: {
        
    },
    data() {
        return {
            open: false
        }
    },
    methods: {
        toggle() {
            this.open = !this.open
        }
    },
    mounted() {
        //log router pathname
        console.log(this.$route.path);
    }


}
 


</script>