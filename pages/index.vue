<script lang="ts" setup>
import { url } from 'inspector';

</script>

<template>
  <div class=" anime_backgorund flex flex-wrap bg-no-repeat bg-contain w-[100%] h-[900px]">
    <div class="mt-9 flex flex-row justify-around space-x-14">
      <h2 class="text-white ml-20">Home</h2>
      <h2 class="text-white">Men</h2>
      <h2 class="text-white">Women</h2>
      <h2 class="text-white">New Arrival</h2>
      <h1 class="absolute text-white font-black font-poppins top-[25px] left-[620px] text-3xl">LOGO</h1>
    </div>
  </div>
  <div>
    <img src="~assets/images/MEN1.png" class="men_image">
      <div class="relative text-center text-black font-poppins left-[500px] mt-56 w-[500px]">
        <h1 class="font-bold text-5xl leading-8 w-[348px] h-[34px] m-8">Anime Merch</h1>
        <p class="font-normal text-base leading-7 w-[433px] h-[151px]">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
        <button class="bg-[#c65dfa] w-[100px] text-white p-[8px] rounded-xl mr-20">Shop Now</button>
      </div>
    <img src="~assets/images/WOMEN1.png" class="women_image">
  </div>
  <div class="text-black mt-80">
    <h1 class="ml-[93px] font-poppins font-medium text-2xl">Just Arrived</h1>
  </div>
  <div class="object-contain flex flex-row justify-between m-[10px] ml-[73px] mr-[73px] mt-[20px] p-4 text-center drop-shadow-lg bg-white border border-gray-200 rounded-lg shadow sm:p-8">
    <div>
      <div class="min-w-full rounded-lg">
        <img class="w-[300px] h-[400px] rounded-lg" src="~assets/images/cast.png"/>
      </div>
      <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">Out Cast T-shirt</h1>
      <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">₹ 299</h1>
    </div>
    <div>
      <div class="min-w-full rounded-lg">
        <img class="w-[300px] h-[400px] rounded-lg" src="~assets/images/eco.png"/>
      </div>
      <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">Eco Over Ego T-shirt</h1>
      <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">₹ 299</h1>
    </div>
    <div>
      <div class="min-w-full rounded-lg">
        <img class="w-[300px] h-[400px] rounded-lg" src="~assets/images/coffee.png"/>
      </div>
      <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">H & F Coffee T-shirt</h1>
      <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">₹ 299</h1>
    </div>
    <div>
      <div class="min-w-full rounded-lg">
        <img class="w-[300px] h-[400px] rounded-lg" src="~assets/images/sink.png"/>
      </div>
      <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">New Sink T-shirt</h1>
      <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">₹ 299</h1>
    </div>
  </div>
  <div class="ml-[47%]"><button class="bg-[#c65dfa] w-[100px] text-white p-[8px] rounded-xl mr-20">View All</button></div>
  <div>
    <img src="~assets/images/Rectangle77.png" class="background_rectangle">
  </div>
  <div class="mt-[60px]">
    <div class="text-black">
      <h1 class="ml-[93px] font-poppins font-medium text-2xl">Featured</h1>
    </div>
    <div class="object-contain flex flex-row justify-between m-[10px] ml-[73px] mr-[73px] mt-[20px] p-4 text-center drop-shadow-lg bg-white border border-gray-200 rounded-lg shadow sm:p-8">
      <div>
        <div class="min-w-full rounded-lg">
          <img class="w-[300px] h-[400px] rounded-lg" src="~assets/images/cast.png"/>
        </div>
        <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">Out Cast T-shirt</h1>
        <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">₹ 299</h1>
      </div>
      <div>
        <div class="min-w-full rounded-lg">
          <img class="w-[300px] h-[400px] rounded-lg" src="~assets/images/eco.png"/>
        </div>
        <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">Eco Over Ego T-shirt</h1>
        <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">₹ 299</h1>
      </div>
      <div>
        <div class="min-w-full rounded-lg">
          <img class="w-[300px] h-[400px] rounded-lg" src="~assets/images/coffee.png"/>
        </div>
        <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">H & F Coffee T-shirt</h1>
        <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">₹ 299</h1>
      </div>
      <div>
        <div class="min-w-full rounded-lg">
          <img class="w-[300px] h-[400px] rounded-lg" src="~assets/images/sink.png"/>
        </div>
        <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">New Sink T-shirt</h1>
        <h1 class="font-poppins text-black text-left ml-[10px] text-[18px]">₹ 299</h1>
      </div>
    </div>
  </div>
  <div class="flex flex-row justify-between ml-[6%] mr-[6%] mt-[60px]">
    <div>
      <div class="border-8 border-black w-[300px] h-[300px] overflow-y-hidden rounded-2xl">
        <img src="~assets/images/Subtract.png">
      </div>
      <h1 class="text-center mt-[5px] text-2xl font-poppins">Anime</h1>
    </div>
    <div>
      <div class="border-8 border-black w-[300px] h-[300px] overflow-y-hidden rounded-2xl">
        <img src="~assets/images/Subtract1.png">
      </div>
      <h1 class="text-center mt-[5px] text-2xl font-poppins">90's</h1>
    </div>
    <div>
      <div class="border-8 border-black w-[300px] h-[300px] overflow-y-hidden rounded-2xl">
        <img src="~assets/images/Subtract2.png">
      </div>
      <h1 class="text-center mt-[5px] text-2xl font-poppins">Typography</h1>
    </div>
    <div>
      <div class="border-8 border-black w-[300px] h-[300px] overflow-y-hidden rounded-2xl">
        <img src="~assets/images/Subtract3.png">
      </div>
      <h1 class="text-center mt-[5px] text-2xl font-poppins">Hindi</h1>
    </div>
  </div>
  <div class="relative bg-contain bg-no-repeat h-[650px] w-[100%] banner mt-[105px]"></div>

  <Footer/>
</template>

<style scoped>
.anime_backgorund{
  background-image: url("/assets/images/Tsting1.png");
}

.men_image{
  position: absolute;
  width: 521px;
  height: 714px;
  left: 0px;
  top: 900px;
}

.women_image{
  position: absolute;
  width: 485px;
  height: 784px;
  right: 0px;
  top: 938px;
}

.background_rectangle{
  position: relative;
  width: 1440px;
  height: 600px;
  margin-top: 110px;
}

.banner{
  background-image: url("assets/images/SUSTAINBANNER1.png");
}

</style>
