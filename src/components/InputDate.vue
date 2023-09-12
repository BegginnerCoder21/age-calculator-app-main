<template>
    <div>
        <form action="" :class="['']" class="space-y-1 flex flex-row space-x-7 items-center border-b-2 caret-violet-400 font-bold border-gray-300 pb-14 md:pb-8 mr-2 relative">
            <div>
                <label for="day"><div class="text-gray-500">Day</div></label>
                <input type="number" placeholder="DD" id="day" name="day"  class="border-[1px] rounded-md focus:border-violet-500 
                                                                        hover:border-violet-500 md:rounded-md outline-none 
                                                                        p-2 md:p-3 border-gray-400 w-16 h-10 md:h-12 text-2xl md:w-28
                                                                        [&::-webkit-inner-spin-button]:appearance-none
                                                                        ">
                <div v-if="false" class="text-xs italic">The fied is required</div>  
            </div>
            <div>
                <label for="month"><div class=" text-gray-500">MONTH</div></label>
                <input type="number" placeholder="MM" id="month" name="month"  class="border-[1px] rounded-md focus:border-violet-500 
                                                                        hover:border-violet-500 md:rounded-md outline-none 
                                                                        p-2 md:p-3 border-gray-400 w-16 h-10 md:h-12 text-2xl md:w-28
                                                                        [&::-webkit-inner-spin-button]:appearance-none ">
                <div v-if="false" class="text-xs italic">The fied is required</div>  
            </div>
            <div>
                <label for="year"><div class=" text-gray-500">YEAR</div></label>
                <input type="number" placeholder="YYYY" id="year" name="year"  class="border-[1px] rounded-md focus:border-violet-500 
                                                                        hover:border-violet-500 md:rounded-md outline-none 
                                                                        p-2 md:p-3 border-gray-400 w-16 h-10 md:h-12 text-2xl  md:w-28
                                                                        [&::-webkit-inner-spin-button]:appearance-none ">
                <div v-if="false" class="text-xs italic">The fied is required</div>  
            </div>
            <button class="absolute top-[88px] md:top-[71px] right-[90px] md:right-0 h-16 w-16 bg-violet-500 hover:bg-black rounded-full">
                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-9 h-9 ml-4 text-white">
                <path stroke-linecap="round" stroke-linejoin="round" d="M15 15l-6 6m0 0l-6-6m6 6V9a6 6 0 0112 0v3" />
                </svg>
            </button>
        </form>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>