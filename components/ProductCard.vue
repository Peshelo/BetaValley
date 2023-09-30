<template>
    <div class="w-full py-4 border-b">
        <div class="flex flex-row">
            <div class="w-fit relative group">
                <img src="https://assets-global.website-files.com/5d3e265ac89f6a3e64292efc/6400bf005945f434370b3bae_miw-desktop%208.webp" class="w-[300px] h-[250px] max-md:w-[300px] max-md:h-[200px] object-cover hover:brightness-50 duration-300"/>
                <div class="group-hover:flex group-hover:flex-col hidden absolute bottom-4 left-2 text-white text-lg font-bold">
                    <h3>Hello</h3>
                    <p class="text-sm text-gray-300 font-regular">Get the latest news</p>
                </div>
            </div>
            <div id="details" class="flex flex-col justify-between mx-4">
                <div class="flex flex-row items-center justify-between mb-2 gap-x-2">
                    <h4 class="text-[30px] max-mdLtext-[25px] font-bold">Tribe</h4>
                    <div class="flex flex-row items-center gap-x-2">
                        <label class="p-2 bg-green-100  px-3 rounded-md bg-gray-200 my-2 w-fit text-xs"><Icon name="material-symbols:arrow-drop-up" class="text-green-400 mr-2" size="20"/>120</label>
                    <label class="p-2 bg-gray-100  px-3 rounded-md bg-gray-200 my-2 w-fit text-xs"><Icon name="mdi:chat" class="text-gray-400 mr-1" size="20"/>12</label>
                    </div>
                 
                </div>
                <label class="text-gray-300 max-md:text-xs">Lorem sfege eg e gegwg chw geg wg egwgegege gewgeewgewgeg w gewgegege...</label>
                <div class="flex flex-row gap-x-2 max-md:hidden">
                    <label class="p-2 rounded-md bg-yellow-200 my-2 w-fit text-xs">Tech Space</label>
                    <label class="p-2 rounded-md bg-green-200 my-2 w-fit text-xs">Tech Space</label>
                    <label class="p-2 rounded-md bg-blue-200 my-2 w-fit text-xs">Tech Space</label>
                </div>
              
                <div class="flex flex-row gap-x-2 max-md:text-sm w-full">
                    <NuxtLink to="/product/1" class="p-2 bg-orange-500  px-2 rounded-md bg-gray-200 my-2 w-fit text-md text-white">View Detials</NuxtLink>
                    <NuxtLink to="/product/1" class="p-2 bg-blue-500  px-2 rounded-md bg-gray-200 my-2 w-fit text-md text-white">Open<Icon name="material-symbols:arrow-outward" class="text-white-400 ml-2" size="25"/></NuxtLink>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>