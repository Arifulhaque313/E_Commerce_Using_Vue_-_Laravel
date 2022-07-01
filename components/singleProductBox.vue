<template>
    <div>
        <div class="div">
                    <div class="slide">
                    <div class="flex product-img justify-center items-center bg-gray-100 p-4 m-4 relative rounded-lg">
                        <div>
                            <img class="w-48 py-4" src="~/assets/images/fresh-fruit.png" alt="">
                        </div>
                        <!-- hover -->
                        <div class="product-img-hover absolute flex rounded-lg items-center justify-center w-full h-full bg-black bg-opacity-60">

                              <div class="">
                                    <div class="flex justify-center items-center mb-4 ">
                                        <button class="border border-white text-lg font-bold text-white rounded-full px-3.5 py-1.5 m-2">-</button>
                                        <button class="bg-white rounded-full px-3.5 py-2 m-2">0</button>
                                        <button class="border border-white text-lg font-bold text-white rounded-full px-3.5 py-1.5 m-2">+</button>
                                    </div>

                                    <div>
                                      <button class="bg-green-500 text-white px-8 py-2 rounded-full">Add To cart</button>
                                    </div>
                              </div>
                        </div>   
                    </div>
                    
                    <div class="text-center mt-4">
                        <h3>Products Name--{{product}}</h3>
                        <p class="text-sm"><span class="text-yellow-500">$200.00 </span><span><del>$300</del></span></p>
                    </div>
                  </div>
                </div>
    </div>
  
</template>

<script>
export default {
    name:"singleProductBox",
    props:[
        "product"
    ]
}
</script>

<style>

</style>