<template>
  <div>
      <div class="container w-full h-28 flex items-center mb-10">
          <div class="w-1/4   flex justify-around items-center p-4">
              <div class="min-w-max">
                    <img width="80" src="~/assets/images/call.png" alt="">
              </div>
              <div class="w-full ml-2 text-black leading-6">
                  <h3 class="font-bold text-sm mb-3">24 Customer Support</h3>
                  <p class="font-thin text-sm">Contact us 24 hours</p>
              </div>
          </div>

          <div class="w-1/4   flex justify-around items-center p-4">
              <div class="min-w-max">
                    <img width="80"  src="~/assets/images/shirt.png" alt="">
              </div>
              <div class="w-full ml-2 text-black">
                  <h3 class="font-bold text-sm mb-3">Authentic Products</h3>
                  <p class="font-thin text-sm">Contact us 24 hours</p>
              </div>
          </div>

          <div class="w-1/4   flex justify-around items-center p-4">
              <div class="min-w-max">
                    <img  width="80" src="~/assets/images/hand4.png" alt="">
              </div>
              <div class="w-full ml-2 text-black">
                  <h3 class="font-bold text-sm mb-3">Secure Payment</h3>
                  <p class="font-thin text-sm">Contact us 24 hours</p>
              </div>
          </div>

          <div class="w-1/4   flex justify-around items-center p-4">
              <div class="min-w-max">
                    <img width="80" src="~/assets/images/setting.png" alt="">
              </div>
              <div class="w-full ml-2 text-black">
                  <h3 class="font-bold text-sm mb-3">Best Prices & Offers</h3>
                  <p class="font-thin text-sm">Contact us 24 hours</p>
              </div>
          </div>
      </div>

      <div class="bg-gray-100 py-14">
         <div class="container">
          <div class=" w-full flex items-center">
              <div class="w-3/5">
                  <Logo/>
                  <p class="my-8 mr-6">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dignissimos quaerat voluptatibus maiores optio porro, suscipit dolores! Minima sed dolorum aut quaerat hic dolores. Quod natus eaque iusto magni fuga explicabo!
                  </p>

                  <div class="flex">
                    <nuxt-link to="" class="mr-4">
                      <img src="~/assets/images/Play_store_badge.png" alt="">
                    </nuxt-link>

                    <nuxt-link to="">
                      <img src="~/assets/images/Apple_badge.png" alt="">
                    </nuxt-link>
                  </div>
              </div>

              <div class="w-1/5">
                  <h3 class="font-medium text-xl mb-3">About Us</h3>
                  <ul class="text-gray font-thin text-sm leading-loose">
                    <li> <nuxt-link to="">About Karte</nuxt-link> </li>
                    <li> <nuxt-link to="">Contact</nuxt-link> </li>
                    <li> <nuxt-link to="">Career</nuxt-link> </li>
                    <li> <nuxt-link to="">Terms & Conditions</nuxt-link> </li>
                    <li> <nuxt-link to="">Category</nuxt-link> </li>
                  </ul>
              </div>

              <div class="w-1/5 ">
                    <h3 class="font-medium text-xl mb-3">Info</h3>
                  <ul class="text-gray font-thin text-sm leading-loose">
                    <li> <nuxt-link to="">Information</nuxt-link> </li>
                    <li> <nuxt-link to="">Shipping</nuxt-link> </li>
                    <li> <nuxt-link to="">Payment</nuxt-link> </li>
                    <li> <nuxt-link to="">Return</nuxt-link> </li>
                    <li> <nuxt-link to="">Blog</nuxt-link> </li>
                  </ul>
              </div>
          </div>
      </div>
      </div>


  </div>
</template>

<script>
export default {
    name:"Footer"
}
</script>

<style>

</style>