<template>
    <div class="hidden lg:block py-6 px-6 bg-[#222222] text-white px-20">
        <div class="flex justify-between items-center ">
            <router-link to="/">
            <h1 class="font-[avenir-black] font-[750]">Easy</h1>
            </router-link>


            <div class="links flex gap-4 items-center font-[350] font-[avenir-light] font-normal">
                <router-link to="/about">
                <p>About</p>
                </router-link>

                <router-link to="/services">
                <p>Services</p>
                </router-link>
                <p>Download</p>


                <router-link to="/signup">
                <div>
                <button class="p-4 px-12 bg-[#F6FF82] font-[750] text-black flex items-center justify-center font-[avenir-black] font-bold">
                    Sign Up
                </button>
                </div>
                </router-link>  
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: "Navbar",
    components: {
        
    },
       mounted() {
        //log router pathname
        console.log(this.$route.path);
    }

}
</script>


<style>
.links a.router-link-active{
    color:#F6FF82
}
</style>