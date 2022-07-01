<template>
    <div>
        <vue-slick-carousel class="hero-slide" :arrows="false" :dots="true">
            <div  class="px-36 py-8 ">
              <div class="bg-green-100 rounded-2xl pt-8 ">
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
            <h3 class="text-2xl mb-2 text-gray-800">Search by Category</h3>
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

        <!-- promo section start  -->
        <div class="container mt-10">
          <div class="flex -mx-4">
              <div class="w-1/2 px-4">
                  <div class="promo_1 bg-center bg-cover px-10 py-10 rounded">
                      <div class="w-2/5 py-10">
                            <p class="text-yellow-500 mb-4">Buy 1 Get 1</p>
                            <h2 class="text-3xl mb-12 font-extrabold text-gray-900">Fresh Fruits Collection</h2>
                            <nuxt-link to="#" class="text-yellow-500 bg-white px-8 py-2 rounded-full">Order now</nuxt-link>
                      </div>
                  </div>
              </div>


              <div class="w-1/2 px-4">
                  <div class="promo_2 bg-center bg-cover px-10 py-10 rounded">
                      <div class="w-2/5 py-10">
                            <p class="text-yellow-500 mb-4">Buy 1 Get 1</p>
                            <h2 class="text-3xl mb-12 font-extrabold text-gray-900">Fresh Fruits Collection</h2>
                            <nuxt-link to="#" class="text-yellow-500 bg-white px-8 py-2 rounded-full">Order now</nuxt-link>
                      </div>
                  </div>
              </div>
          </div>
        </div>
        <!-- promo section finish  -->


        <!-- deals of the week start  -->
        <div class="container mt-10">
            <h3 class="text-2xl mb-2 text-gray-800">Deals of the week</h3>
            <div class="flex items-center">
                <div style="height:3px" class="w-36  bg-green-500"></div>
                <div style="height:1px" class="w-full bg-gray-500"></div>
            </div>

            <vue-slick-carousel class="category-carousel" v-bind="dealsCarouselSettings"> 
                
                <single-product-box v-for="(item, index) in 10" :key="index" :product="item" />


               
              

              <!-- //vegetable-collection.png grocery-items.png -->
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
        
        </div>
        
        <!-- deals of the week end  -->




        <!-- Popular Brand start -->
        <div class="container mt-10">
            <h3 class="text-2xl mb-2 text-gray-800">Popular Brand</h3>
            <div class="flex items-center">
                <div style="height:3px" class="w-36  bg-green-500"></div>
                <div style="height:1px" class="w-full bg-gray-500"></div>
            </div>

          <!-- category carousel start -->
         <vue-slick-carousel class="category-carousel" v-bind="brandCarouselSettings"> 
            <div class="div">
                <div class="pt-8  p-6 m-4 slide">
                <div class="h-10 flex justify-center items-center">
                    <img src="~/assets/images/brand-1.png" alt="">
                </div>
                
              </div>
            </div>

            <div>
              <div class="pt-8  p-6 m-4 slide">
              <div class="h-10 flex justify-center items-center">
                  <img src="~/assets/images/brand-2.png" alt="">
              </div>
              
            </div>
            </div>

            <div>
              <div class="pt-8 p-6 m-4 slide">
              <div class="h-10 flex justify-center items-center">
                  <img src="~/assets/images/brand-3.png" alt="">
              </div>
             
            </div>
            </div>

           <div>
             <div class="pt-8  p-6 m-4 slide">
              <div class="h-10 flex justify-center items-center">
                  <img src="~/assets/images/brand-4.png" alt="">
              </div>
              
            </div>
           </div>

            <div>
              <div class="pt-8  p-6 m-4 slide">
              <div class="h-10 flex justify-center items-center">
                  <img src="~/assets/images/brand-5.png" alt="">
              </div>
              
            </div>
            </div>

           <div>
             <div class="pt-8 px-6 m-4 slide">
              <div class="h-10 flex justify-center items-center">
                  <img src="~/assets/images/brand-6.png" alt="">
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

        
        <div class="container my-10">
          <div class="flex -mx-4">
              <div class="w-1/3 px-4">
                  <div class="promo_1 bg-center bg-cover px-4 py-4 rounded">
                      <div class="w-3/5 py-6 px-4">
                          <h2 class="text-2xl mb-8 font-extrabold text-gray-900">Fresh Fruits Collection</h2>
                           <nuxt-link to="" >
                             <span ><svg  xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 rounded-full p-2 text-yellow-500 bg-white hover:bg-yellow-500 hover:text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                              <path stroke-linecap="round" stroke-linejoin="round" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                            </svg></span>
                           </nuxt-link>       
                      </div>
                  </div>
              </div>


              <div class="w-1/3 px-4">
                  <div class="promo_2 bg-center bg-cover px-4 py-4 rounded">
                      <div class="w-3/5 py-6 px-4">
                          <h2 class="text-2xl mb-8 font-extrabold text-gray-900">Vegetables  Collection</h2>
                           <nuxt-link to="" >
                             <span ><svg  xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 rounded-full p-2 bg-white text-yellow-500 hover:bg-yellow-500 hover:text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                              <path stroke-linecap="round" stroke-linejoin="round" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                            </svg></span>
                           </nuxt-link>       
                      </div>
                  </div>
              </div>

             <div class="w-1/3 px-4">
                  <div class="promo_1 bg-center bg-cover px-4 py-4 rounded">
                      <div class="w-3/5 py-6 px-4">
                          <h2 class="text-2xl mb-8 font-extrabold text-gray-900">Fresh Fruits Collection</h2>
                           <nuxt-link to="" >
                             <span ><svg  xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 rounded-full p-2 bg-white text-yellow-500 hover:bg-yellow-500 hover:text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                              <path stroke-linecap="round" stroke-linejoin="round" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                            </svg></span>
                           </nuxt-link>       
                      </div>
                  </div>
              </div>


          </div>
        </div>


        




        
          
    </div> 
</template>

<script>
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
import Logo from '../components/Logo.vue'
import SingleProductBox from '../components/singleProductBox.vue'
export default {
  name: 'IndexPage',
  components:{
    Header,Footer,Logo,
    SingleProductBox
  },
  data(){
    return{
      categoryCarouselSettings:{
        'slidesToShow':5,
        prevArrow:'>'
      },
      brandCarouselSettings:{
        'slidesToShow':5,
        prevArrow:'>'
        
      },
      dealsCarouselSettings:{
        'slidesToShow':4,
        prevArrow:'>'
      }
    }
  }
}
</script>

<style scoped>
   
</style>
