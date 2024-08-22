<template>
  <div class="text-center bg-white pb-3 rounded-b-lg">
    <div>
      <img width="100%" :src="url" />
    </div>
    <div class="my-2">
      <div class="text-red-500 justify-center flex row text-sm font-bold">
        <div class="mr-2">
          {{ title }}
        </div>
        <div
          v-if="isVideo"
          class="justify-center align-center bg-black rounded-lg"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="white"
            viewBox="0 0 24 24"
            stroke-width="1"
            stroke="black"
            width="32"
            height="32"
            class="size-5"
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
        <div class="text-center description">
          {{ description }}
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const test = "testing";
const props = defineProps({
  url: String,
  title: String,
  description: String,
  isVideo: Boolean,
});
</script>

<style>
.description {
    font-size: 2cqw; width: 90%
}
</style>
