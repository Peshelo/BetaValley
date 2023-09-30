<template>
    <DefaultLayout>
        <div class="page flex flex-row">
            
        <div class="w-5/6 bg-white grid grid-cols-4 max-lg:grid-cols-2 max-sm:grid-cols-1">
            <div class="p-4 col-span-2 flex flex-col justify-between text-white bg-[linear-gradient(to_right_bottom,rgba(0,0,100,0.3),rgba(0,0,100,0.8)),url('https://ichef.bbci.co.uk/news/976/cpsprodpb/13729/production/_112375697_1331db7a-17c0-4401-8cac-6a2309ff49b6.jpg')] bg-gradient-to-r from-cyan-500 to-blue-500 border bg-image">
                <label class="p-2 bg-green-100  px-3 rounded-md bg-gray-200 my-2 w-fit text-xs"><Icon name="material-symbols:arrow-drop-up" class="text-green-400 mr-2" size="20"/>120</label>
                <h2 class="text-md font-bold">Citizens of Earth</h2>
                <p class="text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi labore nemo odio molestias laboriosam? Sequi voluptates iusto enim omnis inventore!...</p>
                <div class="flex flex-row justify-between items-center mt-5 mb-2">
                   <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80" loading="lazy" class="w-[40px] rounded-full border-2" alt="" srcset="">
                    <label class="p-1 bg-gray-100 text-black px-3 rounded-md bg-gray-200 my-2 w-fit text-xs"><Icon name="mdi:chat" class="text-gray-400 mr-1" size="20"/>12</label>
                </div>
            </div>
          <TrendingCard/>
          <TrendingCard/>
          <TrendingCard/>
          <TrendingCard/>
          <TrendingCard/>
          <div class="p-4 row-span-2 flex flex-col justify-between text-white bg-[linear-gradient(to_right_bottom,rgba(0,0,100,0.3),rgba(255,165,50,0.5)),url('https://img.freepik.com/premium-photo/young-creative-woman-virtual-reality-headset-home-digital-technologies-future_717906-1784.jpg')] bg-gradient-to-r from-cyan-500 to-blue-500 border bg-image">
                <label class="p-2 bg-green-100 text-black  px-3 rounded-md bg-gray-200 my-2 w-fit text-xs"><Icon name="material-symbols:arrow-drop-up" class="text-green-400 mr-2" size="20"/>120</label>
                <h2 class="text-md font-bold">Citizens of Earth</h2>
                <p class="text-sm">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi labore nemo odio molestias laboriosam? Sequi voluptates iusto enim omnis inventore!...</p>
                <div class="flex flex-row justify-between items-center mt-5 mb-2">
                   <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80" loading="lazy" class="w-[40px] rounded-full border-2" alt="" srcset="">
                    <label class="p-1 bg-gray-100 text-black px-3 rounded-md bg-gray-200 my-2 w-fit text-xs"><Icon name="mdi:chat" class="text-gray-400 mr-1" size="20"/>12</label>
                </div>
            </div>
            <TrendingCard/>
            <TrendingCard/>
        </div>
        <div class="border-l flex flex-col">
            <label class="font-bold p-2">Recents</label>
            <div class="hover:bg-white duration-300 flex flex-row gap-x-2 text-sm p-3 border-b">
                <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80" loading="lazy" class="w-[40px] h-[40px] object-fit rounded-full border-2" alt="" srcset="">
                <div class="flex flex-col">
                    <label>Peshel Gomo</label>
                    <label class="text-xs text-gray-500">posted "Africa AI"</label>
                </div>
            </div>
            <div class="hover:bg-white duration-300 flex flex-row gap-x-2 text-sm p-3 border-b">
                <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80" loading="lazy" class="w-[40px] h-[40px] object-fit rounded-full border-2" alt="" srcset="">
                <div class="flex flex-col">
                    <label>Peshel Gomo</label>
                    <label class="text-xs text-gray-500">posted "Africa AI"</label>
                </div>
            </div>
            <div class="hover:bg-white duration-300 flex flex-row gap-x-2 text-sm p-3 border-b">
                <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80" loading="lazy" class="w-[40px] h-[40px] object-fit rounded-full border-2" alt="" srcset="">
                <div class="flex flex-col">
                    <label>Peshel Gomo</label>
                    <label class="text-xs text-gray-500">posted "Africa AI"</label>
                </div>
            </div>
            <label class="font-bold p-2">Recents</label>
            <div class="hover:bg-white duration-300 flex flex-row gap-x-2 text-sm p-3 border-b">
                <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80" loading="lazy" class="w-[40px] h-[40px] object-fit rounded-full border-2" alt="" srcset="">
                <div class="flex flex-col">
                    <label>Peshel Gomo</label>
                    <label class="text-xs text-gray-500">posted "Africa AI"</label>
                </div>
            </div>
            <div class="hover:bg-white duration-300 flex flex-row gap-x-2 text-sm p-3 border-b">
                <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80" loading="lazy" class="w-[40px] h-[40px] object-fit rounded-full border-2" alt="" srcset="">
                <div class="flex flex-col">
                    <label>Peshel Gomo</label>
                    <label class="text-xs text-gray-500">posted "Africa AI"</label>
                </div>
            </div>
            <div class="hover:bg-white duration-300 flex flex-row gap-x-2 text-sm p-3 border-b">
                <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80" loading="lazy" class="w-[40px] h-[40px] object-fit rounded-full border-2" alt="" srcset="">
                <div class="flex flex-col">
                    <label>Peshel Gomo</label>
                    <label class="text-xs text-gray-500">posted "Africa AI"</label>
                </div>
            </div>
            
        </div>
    </div>
    </DefaultLayout>
    
</template>

<script setup>
import DefaultLayout from '../layouts/DefaultLayout.vue';
import Trending from '../components/TrendingCard.vue'
</script>