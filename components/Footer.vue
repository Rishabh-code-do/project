<template>
    <div class="h-max w-full mt-5 bg-black text-white p-3 sm:p-6">
        <div class="ml-5 mt-4 lg:hidden">
        <h1 class="font-bold text-4xl">Dank!</h1>
        <p class="font-outfit text-xs">Creating A Vibe You Can Tune In</p>
        </div>
        <hr class="mt-5 lg:hidden">
        <div class="flex flex-col lg:flex-row font-outfit p-3">
            <div class="w-full flex flex-row justify-between mr-auto ml-auto mt-6 lg:mt-24 md:px-16 lg:px-0 xl:px-16 ">
                <ul class="mr-4">
                    <li class="underline text-xs">OUR WORLD</li>
                    <br>
                    <li class="text-xs">ABOUT US</li>
                    <br>
                    <li class="text-xs">OUR STORY</li>
                    <br>
                    <li class="text-xs">OUR STORY</li>
                </ul>
                <ul class="mr-4">
                    <li class="underline text-xs">SUPPORT</li>
                    <br>
                    <li class="text-xs">CONTACT US</li>
                    <br>
                    <li class="text-xs">SHIPPING</li>
                    <br>
                    <li class="text-xs">FAQS</li>
                </ul>
                <ul>
                    <li class="underline text-xs">LEGAL</li>
                    <br>
                    <li class="text-xs">PRIVACY</li>
                    <br>
                    <li class="text-xs ">TERMS & CONDITIONS</li>
                </ul>
                <ul class="hidden sm:block">
                    <li class="underline text-xs">FOLLOW US</li>
                    <br>
                    <li class="text-xs">INSTAGRAM</li>
                    <br>
                    <li class="text-xs">FACEBOOK</li>
                    <br>
                    <li class="text-xs">TWITTER</li>
                </ul>
            </div>
            <div class="block sm:hidden mt-8 flex flex-row">
                <h1 class="text-sm underline font-outfit mr-6 mt-0.5">Follow Us:</h1>
                <img src="~assets/images/instalogo.png" class="h-4 w-4 mr-6 mt-1"/>
                <img src="~assets/images/facebooklogo.png" class="h-6 w-6 mr-6"/>
                <img src="~assets/images/twitterlogo.png" class="h-6 w-6"/>
            </div>
            <hr class="mt-8">

            <div class="border-white mt-10 lg:mt-2 text-center lg:ml-16">
                <h1 class="text-xl">CONTACT US</h1>
                <h3 class="underline text-sm">Let us tackle with your problems.</h3>
                    <div class="w-auto lg:w-96 h-max mt-4 border border-white rounded-2xl mr-auto ml-auto px-4 pb-4">
                    <form class="">
                        <input type="text" id="first_name" class="bg-black mt-3 border-b border-white text-gray-900 text-sm w-full  p-2.5  dark:placeholder-gray-400 dark:text-white " placeholder="Enter Your Name" required>
                        <textarea id="message" rows="3" class="block p-2.5 w-full  mt-4 text-sm text-gray-900 bg-black rounded-lg border border-white dark:placeholder-gray-400 dark:text-white block lg:hidden" placeholder="Type your message..."></textarea>
                        <textarea id="message" rows="8" class="block p-2.5 w-full  mt-4 text-sm text-gray-900 bg-black rounded-lg border border-white dark:placeholder-gray-400 dark:text-white hidden lg:block" placeholder="Type your message..."></textarea>
                        <button class="bg-[#684EBE] p-2 mt-4 w-full rounded-lg"><h1>Submit</h1></button>
                    </form>
                    </div>
            </div>
        </div>
        <div class="font-poppins ml-4 xl:ml-20 hidden lg:block mt-3">
            <h1 class="font-bold text-4xl">Dank!</h1>
            <p class="font-outfit text-xs">Creating A Vibe You Can Tune In</p>
        </div>
        <br><br>
        <hr>
        <div class="mt-3 font-outfit text-sm flex flex-row justify-between " >
            <div class="ml-auto mr-auto lg:ml-3 xl:ml-8">
            <h2>©Dankstore 2023.<br class="hidden lg:block">All rights reserved.</h2>
            </div>
            <div class="hidden lg:block">
                <h1 class="text-sm ml-16">Secure Payments</h1>
                <div class="flex flex-row mt-2">
                    <div class="h-10 w-10 rounded-full border border-white mr-2 p-1"><img src="~assets/images/paylogo.png" class="rounded-xl h-8 w-8"/></div>
                    <div class="h-10 w-10 rounded-full border border-white mr-2 p-2"><img src="~assets/images/paypalLogo.png" class="rounded-xl h-6 w-6"/></div>
                    <div class="h-10 w-10 rounded-full border border-white mr-2 p-1"><img src="~assets/images/paylogo.png" class="rounded-xl h-8 w-8"/></div>
                    <div class="h-10 w-10 rounded-full border border-white p-2"><img src="~assets/images/visalogo.png" class=" h-5 w-5"/></div>
                </div>
            </div>
        </div>
    </div>
    
</template>

<script setup>

</script>

<style scoped>
</style>