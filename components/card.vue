<template>
  <div class="text-center bg-white pb-3 rounded-b-lg">
    <div>
      <img class="w-full" :src="url" />
    </div>
    <div class="my-2">
      <div class="text-red-500 flex justify-center font-extrabold text-xs">
        <div class="mr-2">
          {{ title }}
        </div>
        <div
          v-if="isVideo"
          class="flex justify-center items-center bg-black rounded-lg"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="white"
            viewBox="0 0 24 24"
            stroke-width="1"
            stroke="black"
            width="32"
            height="32"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              d="M5.25 5.653c0-.856.917-1.398 1.667-.986l11.54 6.347a1.125 1.125 0 0 1 0 1.972l-11.54 6.347a1.125 1.125 0 0 1-1.667-.986V5.653Z"
            />
          </svg>
        </div>
      </div>
      <div class="font-bold flex justify-center">
        <div class="text-center text-base w-11/12">
          {{ description }}
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const props = defineProps({
  url: String,
  title: String,
  description: String,
  isVideo: Boolean,
});
</script>
