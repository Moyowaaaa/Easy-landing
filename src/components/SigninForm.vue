<template>
    <div class="w-11/12 lg:w-9/12 mx-auto flex flex-col text-black items-center ">
        <h2 class="text-4xl text-white lg:text-black font-[avenir-md] font-normal">Welcome Back</h2>
        <p class="font-xl text-white lg:text-black ">enter your user details</p>

        <div class="mt-12 w-full flex flex-col gap-4">

           <div class="flex h-[3rem] lg:h-[4rem] items-center justify-between w-full rounded-md bg-[#F6FF82] lg:bg-transparent border-2 border-[#222222] px-6">
            <input type="text" 
            class="w-11/12 bg-transparent border-none outline-none
            placeholder:text-sm
            lg:placeholder:text-xl  placeholder:text-[black] placeholder:font-[avenir-black] placeholder:font-normal"
            placeholder="Email" />

            <div class="">
            <img src="../assets/mail.svg" class=" w-[12px] lg:w-[16px]" />
           </div>
           </div>


           <!-- ----- -->
              <div class="flex h-[3rem] lg:h-[4rem] items-center justify-between w-full rounded-md border-2 border-[#222222] px-6 bg-[#F6FF82] lg:bg-transparent">
            <input type="password" 
            class="w-8/12 bg-transparent border-none outline-none placeholder:font-[avenir-black] placeholder:font-normal   placeholder:text-sm
            lg:placeholder:text-xl  placeholder:text-[black]"
            placeholder="Password" />

            <div class="">
            <img src="../assets/password.svg" class=" w-[12px] lg:w-[16px]" />
           </div>
           </div>

            <router-link to='/' class="w-full">
                <div>
           <!-- <button class="bg-[#222222] text-white py-4 rounded-md font-[avenir-md] font-normal">
           Login
           </button> -->

             <button class="p-2 lg:p-4 px-12 bg-[#222222] text-black text-sm lg:text-base  font-[750] flex items-center justify-center font-[avenir-md] font-normal rounded-md w-full bg-[#F6FF82] lg:bg-[#222222]  lg:text-white">
                    Login
                </button>
           </div>
           </router-link>


           <div class="w-full flex justify-between">
            <div >
            <input type="checkbox"
            class="pr-4"
            ><span class="font-[avenir-black] lg:font-bold text-white lg:text-black text-sm lg:text-base">
                Remember me
            </span>
            
            
            </div>

            <a href="#"><p class="font-[avenir-black] font-bold text-white lg:text-black text-sm lg:text-base">Forgot Password?</p></a>

           </div>

           <div>
            <p class="text-left lg:text-center mt-16 font-[avenir-light] lg:font-[350] text-white lg:text-black text-sm lg:text-base">Don’t have an account? <router-link to="/signup"> <span class="font-[avenir-black] font-bold">Sign Up</span></router-link></p>
           </div>

           
        </div>
    </div>
</template>


<script>


export default {
    name:'SigininForm'
}
</script>


