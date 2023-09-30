<template>
    <DefaultLayout>
        <div class="max-w-[1400px] mx-auto">
              <SliderBanner/>
        <main class="flex flex-row justify-between max-md:flex-col">
            <section id="categories" class="w-1/6 max-md:hidden flex flex-col gap-y-10 px-4">
                <div class="group">
                    <h2 class="font-bold mb-2 border-b py-2">Home</h2>
                    <ul class="flex flex-col gap-y-2 text-gray-600">
                        <li>Friend Activity</li>
                        <li>My Upvotes</li>
                        <li>Collections</li>
                    </ul>
                </div>
                <div class="group">
                    <h2 class="font-bold mb-2 border-b py-2">Home</h2>
                    <ul class="flex flex-col gap-y-2 text-gray-600">
                        <li>Friend Activity</li>
                        <li>My Upvotes</li>
                        <li>Collections</li>
                    </ul>
                </div>
                <div class="group">
                    <h2 class="font-bold mb-2 border-b py-2">Home</h2>
                    <ul class="flex flex-col gap-y-2 text-gray-600">
                        <li>Friend Activity</li>
                        <li>My Upvotes</li>
                        <li>Collections</li>
                    </ul>
                </div>
            </section>

            <!-- Main -->
            <section id="main" class="w-3/6 max-md:w-screen container md:mx-4">
                <div class="flex flex-row items-center justify-between border-b pb-2 border-gray-200">
                    <h2 class="font-bold text-lg">Home</h2>
                    <div id="sorting">
                        <select class="p-2 bg-gray-50">
                            <option>Popular</option>
                            <option>New</option>
                        </select>
                        <select class="p-2 bg-gray-50">
                            <option>Today</option>
                            <option>Today</option>
                        </select>
                    </div>
                </div>
                <div id="productList flex flex-col gap-y-2">
                    <ProductCard/>
                    <ProductCard/>
                    <ProductCard/>
                    <ProductCard/>
                </div>
            </section>
            <section id="activity" class="w-2/6 max-md:w-screen flex flex-col gap-y-4">
                <div class="flex flex-col container">
                    <h3 class="text-[25px] font-bold">Welcome to Beta Valley, friend.</h3>
                    <p class="text-gray-500 text-[20px] my-2">Discover and use the hottest upcoming application and be the first to experience.</p>
                    <button class="bg-blue-600 text-white p-4 rounded-md mt-2 text-lg">Subscribe</button>
                </div>
                <div class="flex flex-col container">
                    <h3 class="text-[25px] font-bold">Top Chart</h3>
                    <p class="text-gray-500 text-[20px] my-2">Discover and use the hottest upcoming application and be the first to experience.</p>
                </div>
            </section>
        </main>
        </div>
      
    </DefaultLayout>
</template>

<script setup>
import SliderBanner from '../components/SliderBanner.vue';
import ProductCard from '../components/ProductCard.vue';
import DefaultLayout from '../layouts/DefaultLayout.vue';


</script>

<style lang="scss" scoped>

</style>