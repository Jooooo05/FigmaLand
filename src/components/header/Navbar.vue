<template>
    <nav class="">
        <div class="fixed top-0 right-0 left-0 ">

            <div class="hidden lg:flex justify-around m-auto w-[800px] xl:w-[1000px] 2xl:w-[1200px] h-[100px] ">

            
            <div class="flex gap-3 items-center">

                <div class="flex text-white gap-5 mr-7">

                <div>
                    <RouterLink class="hover:text-blue-400 hover:border-b hover:border-blue-400 transition-colors duration-100" to="#">Home</RouterLink>
                </div>
                <div>
                    <RouterLink class="hover:text-blue-400 hover:border-b hover:border-blue-400 transition-colors duration-100" to="#">Product</RouterLink>
                </div>
                <div>
                    <RouterLink class="hover:text-blue-400 hover:border-b hover:border-blue-400 transition-colors duration-100" to="#">Pricing</RouterLink>
                </div>
                <div>
                    <RouterLink class="hover:text-blue-400 hover:border-b hover:border-blue-400 transition-colors duration-100" to="#">About</RouterLink>
                </div>
                <div>
                    <RouterLink class="hover:text-blue-400 hover:border-b hover:border-blue-400 transition-colors duration-100" to="#">Contact</RouterLink>
                </div>

                </div>

                <div class="">
                <img src="@/assets/img/logo.png" alt="FigmaLand">
                </div>

            </div>


            <div class="flex justify-center items-center gap-3">
                <div class="cursor-pointer">
                    <img width="30px" height="30px" src="@/assets/img/tweetter.png" alt="tweetter">
                </div>
                <div class="cursor-pointer">
                    <img width="30px" height="30px" src="@/assets/img/facebook.png" alt="tweetter">
                </div>
                <div class="cursor-pointer">
                    <img width="30px" height="30px" src="@/assets/img/linkedin.png" alt="tweetter">
                </div>
            </div>
            </div>

            </div>
    </nav>
</template>

<script>
    export default {
        
    }
</script>