
<template>
  <div class="w-screen sticky top-0 z-10 bg-black px-4 text-white">
    <div
      class="max-w-[1400px] mx-auto flex flex-row items-center justify-between gap-x-4"
    >
      <div class="flex flex-row items-center max-md:py-2">
        <img
          src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcS9WKQ3foNI33b0DsVRjvUTx6MNpdveWu7HqhLDskCdTsEDsWLL"
          width="40"
          class="rounded-full mr-5"
          alt="logo"
        />
        <div class="flex flex-row max-md:hidden">
            <NuxtLink to="/" class="nav">PRODUCTS</NuxtLink>
        <NuxtLink to="/trending/" class="nav">TRENDING</NuxtLink>
        <NuxtLink to="/topUsers/" class="nav">COMMUNITY</NuxtLink>
        <NuxtLink to="/about/" class="nav">ABOUT US</NuxtLink>
        </div>
    
      </div>
      <div class="max-md:hidden flex flex-row items-center gap-x-4">
        <Icon name="mdi:magnify" size="25" class="text-gray-300"/>
        <NuxtLink to="/auth/login" class="p-1 px-5 text-center border-l border-gray-700"><Icon name="material-symbols:account-circle-full" size="17"/></NuxtLink>
        <NuxtLink to="/add/" class="bg-orange-500 text-sm p-2 rounded-md">ADD NEW</NuxtLink>
      </div>
      <div class="md:hidden">
        <Icon @click="showMenu = !showMenu" name="quill:hamburger" size="25"/>
      </div>
    </div>
    <div v-if="showMenu" class="fixed bg-black w-full left-0 z-10 flex flex-col md:hidden">
            <NuxtLink to="/" class="nav">PRODUCTS</NuxtLink>
        <NuxtLink to="/trending" class="nav">TRENDING</NuxtLink>
        <NuxtLink to="/topUsers/" class="nav">COMMUNITY</NuxtLink>
        <NuxtLink to="/about/" class="nav">ABOUT US</NuxtLink>
        </div>
  </div>
</template>

<script setup>
let showMenu = ref(false);
</script>

<style>
.sticka{
    position: --websticky--;
    position: sticky;
    top:0;
    z-index:20px
}
</style>
