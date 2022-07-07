<template>
    <div class="w-full flex h-screen bg-[#F6FF82]">

        <div class=" w-6/12 bg-[#222222] hidden flex-col text-white justify-center lg:flex">
            <div class="pl-24">
             <h1 class="font-[750] text-7xl font-[avenir-heavy]">Easy</h1>
            <p class="mb-6 font-[gotham-light] font-[400]">All your expenses and expected income all in one place.</p>
            </div>  
            <img src="../assets/LoginCard.svg" class="h-[70%]" />
        </div>


        <div class="w-full bg-[#222222] h-full justify-center lg:justify-start  pt-12 flex flex-col items-center lg:pt-[20vh] lg:w-6/12  lg:bg-[#F6FF82]">
            <SigninForm />
        </div>
        



    </div>
</template>


<script>

import SigninForm from '@/components/SigninForm.vue'

export default {
  components: { SigninForm },
    
}
</script>

<style scoped>

</style>