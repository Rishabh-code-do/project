<template>
    <Navbar />
    <div class="lg:flex lg:flex-row lg:w-max ml-auto mr-auto">
        <div>
            <div class="w-max lg:w-max mt-16 mr-auto ml-auto lg:mr-4 xl:mr-28 justify-between p-2 drop-shadow-lg bg-white border border-gray-200 rounded-lg shadow">
                <div class="flex flex-row">
                    <div class="w-20"><img class="w-20 h-24 rounded-lg" src="~assets/images/cast.png"></div>
                    <div class="mr-aut0 ml-auto flex flex-col md:flex-row">
                        <div class="ml-4 sm:ml-8">
                            <h1 class="font-normal text-lg font-poppins">Out Cast T-shirt</h1>
                            <h3 class="font-normal text-xs font-poppins">Out Cast T-shirt</h3>
                        </div>
                        <div class="flex flex-row justify-between mt-5 md:mt-2">
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-4 sm:ml-8 lg:ml-8 xl:ml-20 p-1 rounded-lg">
                                <label for="size">Size:</label>
                                <select name="cars" id="cars">
                                    <option value="xsmall">XS</option>
                                    <option value="small">S</option>
                                    <option value="medium">M</option>
                                    <option value="large">L</option>
                                    <option value="xlarge">XL</option>
                                    <option value="xxlarge">XXL</option>
                                </select>
                            </div>
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-2 sm:ml-4 lg:mr-8 xl:mr-20 p-1 rounded-lg">
                                <button class="m-auto" @click="count--">-</button>
                                <h2 class="m-auto">{{count}}</h2>
                                <button class="m-auto" @click="count++">+</button>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-col justify-between">
                        <div class="ml-3 sm:ml-6 mt-2">
                            <h2>₹ 698</h2>
                        </div>
                        <div class="ml-4 sm:ml-8">
                            <button><p class="text-xs text-[#666666]">Remove</p></button>
                        </div>
                    </div>
                </div>
                <hr class="mt-4 mb-4">
                <div class="flex flex-row">
                    <div class="w-20"><img class="w-20 h-24 rounded-lg" src="~assets/images/cast.png"></div>
                    <div class="mr-aut0 ml-auto flex flex-col md:flex-row">
                        <div class="ml-4 sm:ml-8">
                            <h1 class="font-normal text-lg font-poppins">Out Cast T-shirt</h1>
                            <h3 class="font-normal text-xs font-poppins">Out Cast T-shirt</h3>
                        </div>
                        <div class="flex flex-row justify-between mt-5 md:mt-2">
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-4 sm:ml-8 lg:ml-8 xl:ml-20 p-1 rounded-lg">
                                <label for="size">Size:</label>
                                <select name="cars" id="cars">
                                    <option value="xsmall">XS</option>
                                    <option value="small">S</option>
                                    <option value="medium">M</option>
                                    <option value="large">L</option>
                                    <option value="xlarge">XL</option>
                                    <option value="xxlarge">XXL</option>
                                </select>
                            </div>
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-2 sm:ml-4 lg:mr-8 xl:mr-20 p-1 rounded-lg">
                                <button class="m-auto" @click="count--">-</button>
                                <h2 class="m-auto">{{count}}</h2>
                                <button class="m-auto" @click="count++">+</button>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-col justify-between">
                        <div class="ml-3 sm:ml-6 mt-2">
                            <h2>₹ 698</h2>
                        </div>
                        <div class="ml-4 sm:ml-8">
                            <button><p class="text-xs text-[#666666]">Remove</p></button>
                        </div>
                    </div>
                </div>
                <hr class="mt-4 mb-4">
                <div class="flex flex-row">
                    <div class="w-20"><img class="w-20 h-24 rounded-lg" src="~assets/images/cast.png"></div>
                    <div class="mr-aut0 ml-auto flex flex-col md:flex-row">
                        <div class="ml-4 sm:ml-8">
                            <h1 class="font-normal text-lg font-poppins">Out Cast T-shirt</h1>
                            <h3 class="font-normal text-xs font-poppins">Out Cast T-shirt</h3>
                        </div>
                        <div class="flex flex-row justify-between mt-5 md:mt-2">
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-4 sm:ml-8 lg:ml-8 xl:ml-20 p-1 rounded-lg">
                                <label for="size">Size:</label>
                                <select name="cars" id="cars">
                                    <option value="xsmall">XS</option>
                                    <option value="small">S</option>
                                    <option value="medium">M</option>
                                    <option value="large">L</option>
                                    <option value="xlarge">XL</option>
                                    <option value="xxlarge">XXL</option>
                                </select>
                            </div>
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-2 sm:ml-4 lg:mr-8 xl:mr-20 p-1 rounded-lg">
                                <button class="m-auto" @click="count--">-</button>
                                <h2 class="m-auto">{{count}}</h2>
                                <button class="m-auto" @click="count++">+</button>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-col justify-between">
                        <div class="ml-3 sm:ml-6 mt-2">
                            <h2>₹ 698</h2>
                        </div>
                        <div class="ml-4 sm:ml-8">
                            <button><p class="text-xs text-[#666666]">Remove</p></button>
                        </div>
                    </div>
                </div>
                <hr class="mt-4 mb-4">
                <div class="flex flex-row">
                    <div class="w-20"><img class="w-20 h-24 rounded-lg" src="~assets/images/cast.png"></div>
                    <div class="mr-aut0 ml-auto flex flex-col md:flex-row">
                        <div class="ml-4 sm:ml-8">
                            <h1 class="font-normal text-lg font-poppins">Out Cast T-shirt</h1>
                            <h3 class="font-normal text-xs font-poppins">Out Cast T-shirt</h3>
                        </div>
                        <div class="flex flex-row justify-between mt-5 md:mt-2">
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-4 sm:ml-8 lg:ml-8 xl:ml-20 p-1 rounded-lg">
                                <label for="size">Size:</label>
                                <select name="cars" id="cars">
                                    <option value="xsmall">XS</option>
                                    <option value="small">S</option>
                                    <option value="medium">M</option>
                                    <option value="large">L</option>
                                    <option value="xlarge">XL</option>
                                    <option value="xxlarge">XXL</option>
                                </select>
                            </div>
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-2 sm:ml-4 lg:mr-8 xl:mr-20 p-1 rounded-lg">
                                <button class="m-auto" @click="count--">-</button>
                                <h2 class="m-auto">{{count}}</h2>
                                <button class="m-auto" @click="count++">+</button>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-col justify-between">
                        <div class="ml-3 sm:ml-6 mt-2">
                            <h2>₹ 698</h2>
                        </div>
                        <div class="ml-4 sm:ml-8">
                            <button><p class="text-xs text-[#666666]">Remove</p></button>
                        </div>
                    </div>
                </div>
                <hr class="mt-4 mb-4">
                <div class="flex flex-row">
                    <div class="w-20"><img class="w-20 h-24 rounded-lg" src="~assets/images/cast.png"></div>
                    <div class="mr-aut0 ml-auto flex flex-col md:flex-row">
                        <div class="ml-4 sm:ml-8">
                            <h1 class="font-normal text-lg font-poppins">Out Cast T-shirt</h1>
                            <h3 class="font-normal text-xs font-poppins">Out Cast T-shirt</h3>
                        </div>
                        <div class="flex flex-row justify-between mt-5 md:mt-2">
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-4 sm:ml-8 lg:ml-8 xl:ml-20 p-1 rounded-lg">
                                <label for="size">Size:</label>
                                <select name="cars" id="cars">
                                    <option value="xsmall">XS</option>
                                    <option value="small">S</option>
                                    <option value="medium">M</option>
                                    <option value="large">L</option>
                                    <option value="xlarge">XL</option>
                                    <option value="xxlarge">XXL</option>
                                </select>
                            </div>
                            <div class="w-24 md:h-9 border border-[#BBBBBB] flex flex-row ml-2 sm:ml-4 lg:mr-8 xl:mr-20 p-1 rounded-lg">
                                <button class="m-auto" @click="count--">-</button>
                                <h2 class="m-auto">{{count}}</h2>
                                <button class="m-auto" @click="count++">+</button>
                            </div>
                        </div>
                    </div>
                    <div class="flex flex-col justify-between">
                        <div class="ml-3 sm:ml-6 mt-2">
                            <h2>₹ 698</h2>
                        </div>
                        <div class="ml-4 sm:ml-8">
                            <button><p class="text-xs text-[#666666]">Remove</p></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="lg:ml-auto lg:mr-auto lg:mt-16">
            <div class="w-max sm:w-96 md:w-[560px] lg:w-max mt-8 border border-black ml-auto mr-auto p-3 px-4 rounded-lg">
                <h1>Delivery Location</h1>
                <form class="flex flex-row mt-3"> 
                    <input class="w-64 sm:w-full md:w-full lg:w-64 border border-black p-2.5 rounded-lg">
                    <button class="bg-[#684EBE] text-white p-2.5 ml-2 px-3.5 rounded-lg"><PencilIcon class="h-6 w-6" aria-hidden="true"/></button>
                </form>
            </div>
            <div class="w-max sm:w-96 md:w-[560px] lg:w-max mt-5 border border-black ml-auto mr-auto p-3 px-4 rounded-lg">
                <h1>Apply Coupon</h1>
                <form class="flex flex-row mt-3"> 
                    <input class="w-64 sm:w-full md:w-full lg:w-64 border border-black p-2.5 rounded-lg">
                    <button class="bg-[#684EBE] text-white p-2.5 px-3.5 ml-2 rounded-lg"><CheckIcon class="h-6 w-6" aria-hidden="true"/></button>
                </form>
            </div>
            <div class="w-96 md:w-[580px] lg:w-96 mt-4 ml-auto mr-auto px-4">
                <h1>Billing details</h1>
            </div>
            <div class="w-max sm:w-96 md:w-[560px] lg:w-max mt-2 border border-black ml-auto mr-auto p-3 px-4 rounded-lg font-poppins">
                <div class="w-80 sm:w-full md:w-full lg:w-80 flex flex-row justify-between"><h1>Cart Total</h1><h1>₹ 598</h1></div>
                <div class="w-80 sm:w-full md:w-full lg:w-80 flex flex-row justify-between mt-4"><h1>Shipping Charges</h1><h1>₹ 60</h1></div>
                <hr class="h-1 mt-2 mb-2">
                <div class="font-bold flex flex-row justify-between">
                    <h1>Grand Total</h1>
                    <h1>₹ 658</h1>
                </div>   
            </div>
            <div class="w-80 sm:w-96 md:w-[540px] lg:w-80 ml-auto mr-auto mt-5">
                <Button class="w-80 sm:w-96 md:w-[540px] lg:w-80 bg-[#684EBE] text-white p-2 rounded-lg">Place Order</Button>
            </div>
        </div>
    </div>
    <Footer/>
</template>

<script setup>
import { ref } from 'vue'
import { PencilIcon,CheckIcon } from "@heroicons/vue/24/solid"

const count = ref(1)

</script>

<style scoped>

</style>