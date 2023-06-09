<template>
    <Navbar/>
    <div class="block lg:hidden">
        <div class="w-full h-16 border-b-2 border-indigo-500 shadow-sm p-2 flex flex-row">
            <div class="w-12 h-12 ml-5 sm:ml-16 md:ml-24 rounded-lg bg-[#684EBE]"> 
                <div>
                <h1 class="text-white ml-3.5 font-bold">Da</h1>
                <h1 class="text-white ml-3.5 font-bold">nk</h1>
                </div>
            </div>
            <div>
                <h1 class="font-bold text-xl ml-5 text-[#01010F] font-poppins">User Name</h1>
                <h2 class="text-sm ml-5 text-[#01010F] font-poppins">example@gmail.com</h2>
            </div>
        </div>
        <div class="p-2 mt-2 sm:px-6 md:px-12">
            <div class="w-full h-max border shadow-md rounded-lg">
                <button class="w-full">
                    <div class="flex flex-row p-4 border-b justify-between">
                        <div class="flex flex-row">
                            <UserIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5"/>
                            <h1 class="text-lg">Profile</h1>
                        </div>
                        <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5"/>
                    </div>
                </button>
                <button class="w-full">
                    <div class="flex flex-row p-4 border-b justify-between">
                        <div class="flex flex-row">
                            <CogIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5"/>
                            <h1 class="text-lg">Orders</h1>
                        </div>
                        <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5"/>
                    </div>
                </button>
                <button class="w-full">
                    <div class="flex flex-row p-4 border-b justify-between">
                        <div class="flex flex-row">
                            <CogIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5"/>
                            <h1 class="text-lg">Address</h1>
                        </div>
                        <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5"/>
                    </div>
                </button>
                <button class="w-full">
                    <div class="flex flex-row p-4 border-b justify-between">
                        <div class="flex flex-row">
                            <HeartIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5"/>
                            <h1 class="text-lg">Wishlist</h1>
                        </div>
                        <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5"/>
                    </div>
                </button>
                <button class="w-full">
                    <div class="flex flex-row p-4 border-b justify-between">
                        <div class="flex flex-row">
                            <BellIcon  class="h-6 w-6 mr-5 mt-0.5 sm:ml-5"/>
                            <h1 class="text-lg">Notifications</h1>
                        </div>
                        <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5"/>
                    </div>
                </button>
                <button class="w-full">
                    <div class="flex flex-row p-4 justify-between">
                        <div class="flex flex-row">
                        <CogIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5"/>
                        <h1 class="text-lg">Setting</h1>
                        </div>
                        <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5"/>
                    </div>
                </button>
            </div>
            <button class="w-full border border-[#684EBE] p-2 text-[#684EBE] font-bold text-lg rounded-lg mt-4">Log out</button>
        </div>
    </div>
    <div class="hidden lg:block">
        <div class="flex flex-row">
            <div class="xl:ml-2 lg:ml-0">
                <div class="ml-6 xl:ml-7 mt-10 border w-72 xl:w-80 p-3 rounded-lg shadow-md">
                    <h1 class="font-bold text-xl ml-2 text-[#684EBE] font-poppins">User Name</h1>
                    <h2 class="text-sm ml-2 text-[#01010F] font-poppins">example@gmail.com</h2>
                </div>
                <AccountOption/>
            </div>
            <div class="border shadow-md p-2 rounded-lg border-[#684EBE] mt-10 w-full h-max">
                <h1 class="font-bold text-md">Edit Profile</h1>
                <div class="grid grid-cols-1 xl:grid-cols-2 gap-4 mt-2">
                    <div class="w-full h-12 border rounded-lg"><input class="w-full border border-black h-12 p-1 px-2 text-xl text-black rounded-lg" placeholder="Name"></div>
                    <div class="w-full h-12 border rounded-lg"><input class="w-full border border-black h-12 p-1 px-2 text-xl text-black rounded-lg" placeholder="Phone"></div>
                    <div class="w-full h-12 border rounded-lg"><input class="w-full border border-black h-12 p-1 px-2 text-xl text-black rounded-lg" placeholder="Email"></div>
                    <div class="w-full h-12 border rounded-lg"><input class="w-full border border-black h-12 p-1 px-2 text-xl text-black rounded-lg" placeholder="DOB"></div>
                    <div class="w-full h-12 border rounded-lg"><input class="w-full border border-black h-12 p-1 px-2 text-xl text-black rounded-lg" placeholder="Gender"></div>
                    <div class="w-full h-12 border rounded-lg"><button class="w-full h-12 border rounded-lg bg-[#684EBE] text-white">UPDATE</button></div>
                </div>
            </div>
            <div class="px-4 xl:px-8 2xl:px-12">
                <div class="w-72 xl:w-80 h-max mt-10 border rounded-lg shadow-md p-4 py-6">
                    <h1 class="text-xl font-poppins">Orders</h1>
                    <div class="w-full h-max border rounded-lg shadow-md p-2 mt-2">
                        <div class="flex flex-row">
                            <img src="~assets/images/order.png" class="w-12 h-12 rounded-lg">
                            <div class="ml-2">
                                <h2 class="font-bold text-xs">Product Name</h2>
                                <h4 class="text-xs">Description</h4>
                                <h6 class="text-xs text-[#58C563]">Delivery Est. on 22 June</h6>
                            </div>
                        </div>
                    </div>
                    <div class="w-full h-max border rounded-lg shadow-md p-2 mt-3">
                        <div class="flex flex-row">
                            <img src="~assets/images/order.png" class="w-12 h-12 rounded-lg">
                            <div class="ml-2">
                                <h2 class="font-bold text-xs">Product Name</h2>
                                <h4 class="text-xs">Description</h4>
                                <h6 class="text-xs text-[#58C563]">Delivery Est. on 22 June</h6>
                            </div>
                        </div>
                    </div>
                    <div class="w-full h-max border rounded-lg shadow-md p-2 mt-3">
                        <div class="flex flex-row">
                            <img src="~assets/images/order.png" class="w-12 h-12 rounded-lg">
                            <div class="ml-2">
                                <h2 class="font-bold text-xs">Product Name</h2>
                                <h4 class="text-xs">Description</h4>
                                <h6 class="text-xs text-[#58C563]">Delivery Est. on 22 June</h6>
                            </div>
                        </div>
                    </div>
                    <div class="w-full h-max border rounded-lg shadow-md p-2 mt-3">
                        <div class="flex flex-row">
                            <img src="~assets/images/order.png" class="w-12 h-12 rounded-lg">
                            <div class="ml-2">
                                <h2 class="font-bold text-xs">Product Name</h2>
                                <h4 class="text-xs">Description</h4>
                                <h6 class="text-xs text-[#58C563]">Delivery Est. on 22 June</h6>
                            </div>
                        </div>
                    </div>
                    <div class="w-full h-max border rounded-lg shadow-md p-2 mt-3">
                        <div class="flex flex-row">
                            <img src="~assets/images/order.png" class="w-12 h-12 rounded-lg">
                            <div class="ml-2">
                                <h2 class="font-bold text-xs">Product Name</h2>
                                <h4 class="text-xs">Description</h4>
                                <h6 class="text-xs text-[#58C563]">Delivery Est. on 22 June</h6>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { ChevronRightIcon,CogIcon,UserIcon,HeartIcon,BellIcon  } from "@heroicons/vue/24/outline"
</script>

<style scoped>

</style>