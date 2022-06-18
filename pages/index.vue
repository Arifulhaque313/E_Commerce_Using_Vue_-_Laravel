<template>
<div>
    <vue-slick-carousel class="hero-slide" :arrows="false" :dots="true">
        <div  class="px-28 py-8 ">
          <div class="bg-green-100 rounded-2xl pt-8">
              <div class="container">
                <div class="flex items-center">
                  <div class="w-1/2 mr-6">
                      <p class="text-green-600 text-2xl font-normal">Save up 30% off</p>
                      <h2 class="text-5xl font-bold text-gray-800 py-4">
                        Bengal Vegetable Farm Organic 100%
                      </h2>
                      <p class="pb-10 pt-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum sed obcaecati odio consequatur fuga?</p>

                      <nuxt-link to="" class="rounded-full px-8 py-2 bg-green-500 text-white text-base">Shop now</nuxt-link>
                  </div>
                  
                  <div class="w-1/2 flex justify-end">
                      <img width="500" src="~/assets/images/hero.png" alt="">
                  </div>
              </div>
              </div>
          </div>
      </div>   

         <div  class="px-28 py-8">
          <div class="bg-green-100 rounded-2xl pt-8">
              <div class="container">
                <div class="flex items-center">
                  <div class="w-1/2 mr-6">
                      <p class="text-green-600 text-2xl font-normal">Save up 40% off</p>
                      <h2 class="text-5xl font-bold text-gray-800 py-4">
                        Bengal Vegetable Farm Organic 100%
                      </h2>
                      <p class="pb-10 pt-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum sed obcaecati odio consequatur fuga?</p>

                      <nuxt-link to="" class="rounded-full px-8 py-2 bg-green-500 text-white text-base">Shop now</nuxt-link>
                  </div>
                  
                  <div class="w-1/2 flex justify-end">
                      <img width="500" src="~/assets/images/hero.png" alt="">
                  </div>
              </div>
              </div>
          </div>
      </div> 

         <div  class="px-28 py-8">
          <div class="bg-green-100 rounded-2xl pt-8">
              <div class="container">
                <div class="flex items-center">
                  <div class="w-1/2 mr-6">
                      <p class="text-green-600 text-2xl font-normal">Save up 50% off</p>
                      <h2 class="text-5xl font-bold text-gray-800 py-4">
                        Bengal Vegetable Farm Organic 100%
                      </h2>
                      <p class="pb-10 pt-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum sed obcaecati odio consequatur fuga?</p>

                      <nuxt-link to="" class="rounded-full px-8 py-2 bg-green-500 text-white text-base">Shop now</nuxt-link>
                  </div>
                  
                  <div class="w-1/2 flex justify-end">
                      <img width="500" src="~/assets/images/hero.png" alt="">
                  </div>
              </div>
              </div>
          </div>
      </div> 
    </vue-slick-carousel>
    
</div>
  
  
</template>

<script>
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
import Logo from '../components/Logo.vue'
export default {
  name: 'IndexPage',
  components:{
    Header,Footer,Logo
  }
}
</script>

<style scoped>
   
</style>
