<template>
    <div>
        <div class="container ">
           <!-- hearder first part start -->
            <div class="flex justify-between items-center py-6">
                <Logo/>

                <div class="w-96">
                    <div class="border border-gray-red-500 p-1 flex rounded-full items-center">
                        <div class="min-w-max">
                            <img src="~/assets/images/search.png" alt="">
                        </div>
                        <input class="w-full px-3 py-1 focus:outline-none" type="search" placeholder="serarch here ...">

                        <button class="bg-gray-600 text-white rounded-full px-6 py-1 " type="submit">Search</button>
                    </div>
                </div>

                <div class="min-w-max flex items-center">
                    <nuxt-link to="/"><span class="bs-icon-box rounded-full hover:bg-gray-400 inline-block flex intems center justify-center p-2"><img  src="~/assets/images/heart.png" alt=""></span></nuxt-link>
                    <nuxt-link to="/" class="relative"><span class=" mx-4 bs-icon-box rounded-full hover:bg-gray-400 inline-block flex intems center justify-center p-2"><img  src="~/assets/images/u_shopping-bag.png" alt=""></span> <span class="absolute bg-red-500 h-4 w-4 text-white rounded-full flex justify-center items-center top-0 right-0">0</span></nuxt-link>
                    <nuxt-link to="/" class="flex items-center"><span class="bs-icon-box rounded-full hover:bg-gray-400 inline-block flex intems center justify-center p-3"><img  src="~/assets/images/user.png" alt=""></span> <span>Account</span></nuxt-link>
                </div>
           </div>
           <!-- hearder first part end -->
            
            <!-- Header second section start  -->
             <div class="flex items-center justify-between">
                <div class="w-96  bg-green-400 flex items-center py-2 px-3 rounded-full cursor-pointer">
                    <div class="min-w-max">
                        <img src="~assets/images/menu-right.png" alt="">
                    </div>
                    <div class="w-full text-center text-white mx-6">
                        Categoriess
                    </div>

                    <div class="min-w-max">
                        <img src="~assets/images/chevron-down.png" alt="">
                    </div>
                </div>

                <div class="w-full">
                    <ul class="flex items-center justify-center">
                        <li class="p-4"><nuxt-link to="/">Home</nuxt-link></li>
                        <li class="p-4"><nuxt-link to="/">Shop</nuxt-link></li>
                        <li class="p-4"><nuxt-link to="/">Pages</nuxt-link></li>
                        <li class="p-4"><nuxt-link to="/">Contact</nuxt-link></li>
                        <li class="p-4"><nuxt-link to="/">Track Order</nuxt-link></li>
                    </ul>
                </div>

                <div class="min-w-max flex items-center  bs-orange-color">
                    <div class="bs-orange-bg">
                        <img src="~assets/images/u_percentage.png" alt="">
                    </div>
                    <div class="ml-3">Special Offer</div>
                </div>
            </div>
            <!-- Header second section end  -->
           

        </div>
        
    </div>
</template>

<script>
export default {
    name:"Header",
}
</script>

<style>

</style>