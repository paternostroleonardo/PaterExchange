<template>
  <header class="shadow w-screen">
    <nav>
      <nav class="justify-center bg-blue-400 p-2">
        <div class="flex items-center flex-shrink-0 text-white">
          <px-icon class="mr-1" />
          <router-link  :to="{ name: 'home' }" class="font-semibold text-3xl tracking-tight">PaterExchange
          </router-link>
        </div>
           <div class="flex justify-center text-white inline-block">
             <router-link  :to="{ name: 'home' }" class="font-semibold text-1xl tracking-tight">Made By <span class="text-yellow-300 inline-block"> Pater </span>
               <img class="inline-block w-6 mx-1 tracking-tight text-right" src="https://images.emojiterra.com/google/android-11/512px/1f525.png" alt="" />
          </router-link>
             </div>
        <div class="hidden sm:block w-full block flex-grow lg:flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow"></div>
        </div>
      </nav>
    </nav>
  </header>
</template>
<script>
import PxIcon from "@/components/PxIcon";
export default {
  name: 'PxHeader',
  components: { PxIcon }
}
</script>