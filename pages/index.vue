<template>
    <div>
        <vue-slick-carousel class="hero-slide" :arrows="false" :dots="true">
            <div  class="px-48 py-8 ">
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

            <div  class="px-48 py-8">
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

            <div  class="px-48 py-8">
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

        <!-- search by category section start -->
        <div class="container ">
            <h3 class="text-3xl mb-6 text-gray-800">Search by Category</h3>
            <div class="flex items-center">
                <div style="height:3px" class="w-36  bg-green-500"></div>
                <div style="height:1px" class="w-full bg-gray-500"></div>
            </div>

            <!-- category carousel start -->
         <vue-slick-carousel class="category-carousel" v-bind="categoryCarouselSettings"> 
            <div class="div">
                <div class="bg-gray-200 p-4 m-4 slide">
                <div class="h-32 flex justify-center items-center">
                    <img src="~/assets/images/caro1.png" alt="">
                </div>
                <div class="text-center">
                    <h3>Groceries</h3>
                </div>
              </div>
            </div>

            <div>
              <div class="bg-gray-200 p-4 m-4 slide">
              <div class="h-32 flex justify-center items-center">
                  <img src="~/assets/images/caro2.png" alt="">
              </div>
              <div class="text-center">
                  <h3>Groceries</h3>
              </div>
            </div>
            </div>

            <div>
              <div class="bg-gray-200 p-4 m-4 slide">
              <div class="h-32 flex justify-center items-center">
                  <img src="~/assets/images/caro3.png" alt="">
              </div>
              <div class="text-center">
                  <h3>Groceries</h3>
              </div>
            </div>
            </div>

           <div>
             <div class="bg-gray-200 p-4 m-4 slide">
              <div class="h-32 flex justify-center items-center">
                  <img src="~/assets/images/caro4.png" alt="">
              </div>
              <div class="text-center">
                  <h3>Groceries</h3>
              </div>
            </div>
           </div>

            <div>
              <div class="bg-gray-200 p-4 m-4 slide">
              <div class="h-32 flex justify-center items-center">
                  <img src="~/assets/images/caro5.png" alt="">
              </div>
              <div class="text-center">
                  <h3>Groceries</h3>
              </div>
            </div>
            </div>

           <div>
             <div class="bg-gray-200 p-4 m-4 slide">
              <div class="h-32 flex justify-center items-center">
                  <img src="~/assets/images/caro6.png" alt="">
              </div>
              <div class="text-center">
                  <h3>Groceries</h3>
              </div>
            </div>
           </div>


             <template #prevArrow="arrowOption">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7" />
                </svg>
             </template>

             <template #nextArrow="arrowOption">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7" />
                </svg>
             </template>

              
         </vue-slick-carousel>

        <!-- category carousel end  -->
        </div>
        <!-- search by category section end  -->

        

        
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
  },
  data(){
    return{
      categoryCarouselSettings:{
        'slidesToShow':5,
        prevArrow:'>'
        
      }
    }
  }
}
</script>

<style scoped>
   
</style>
