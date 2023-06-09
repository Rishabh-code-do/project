<template>
    <div class="p-2 mt-2 sm:px-6 md:px-12 lg:px-6 xl:px-7">
        <div class="w-full lg:w-72 xl:w-80 h-max border shadow-md rounded-lg">
            <button class="w-full">
                <div class="flex flex-row p-4 border-b justify-between">
                    <div class="flex flex-row">
                        <UserIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5 lg:ml-0"/>
                        <h1 class="text-lg">Profile</h1>
                    </div>
                    <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5 block lg:hidden"/>
                </div>
            </button>
            <button class="w-full">
                <div class="flex flex-row p-4 border-b justify-between">
                    <div class="flex flex-row">
                        <CogIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5 lg:ml-0"/>
                        <h1 class="text-lg">Orders</h1>
                    </div>
                    <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5 block lg:hidden"/>
                </div>
            </button>
            <button class="w-full">
                <div class="flex flex-row p-4 border-b justify-between">
                    <div class="flex flex-row">
                        <CogIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5 lg:ml-0"/>
                        <h1 class="text-lg">Address</h1>
                    </div>
                    <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5 block lg:hidden"/>
                </div>
            </button>
            <button class="w-full">
                <div class="flex flex-row p-4 border-b justify-between">
                    <div class="flex flex-row">
                        <HeartIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5 lg:ml-0"/>
                        <h1 class="text-lg">Wishlist</h1>
                    </div>
                    <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5 block lg:hidden"/>
                </div>
            </button>
            <button class="w-full">
                <div class="flex flex-row p-4 border-b justify-between">
                    <div class="flex flex-row">
                        <BellIcon  class="h-6 w-6 mr-5 mt-0.5 sm:ml-5 lg:ml-0"/>
                        <h1 class="text-lg">Notifications</h1>
                    </div>
                    <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5 block lg:hidden"/>
                </div>
            </button>
            <button class="w-full">
                <div class="flex flex-row p-4 justify-between">
                    <div class="flex flex-row">
                    <CogIcon class="h-6 w-6 mr-5 mt-0.5 sm:ml-5 lg:ml-0"/>
                    <h1 class="text-lg">Setting</h1>
                    </div>
                    <ChevronRightIcon class="h-5 w-5 mt-1 sm:mr-5 block lg:hidden"/>
                </div>
            </button>
        </div>
        <button class="w-full lg:w-72 xl:w-80 border border-[#684EBE] p-2 text-[#684EBE] font-bold text-lg rounded-lg mt-4">Log out</button>
    </div>
</template>

<script setup>
import { ChevronRightIcon,CogIcon,UserIcon,HeartIcon,BellIcon  } from "@heroicons/vue/24/outline"
</script>

<style scoped>

</style>