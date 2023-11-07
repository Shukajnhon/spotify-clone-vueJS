<script setup>
import {toRefs} from 'vue';
import {RouterLink} from 'vue-router';

const props = defineProps({
  image: String,
  title: String,
  subTitle: String,
});

const {image, title, subTitle} = toRefs(props);
</script>

<template>
  <RouterLink to="library">
    <div class="p-4 bg-[#111] rounded-md m-2 hover:bg-[#252525] cursor-pointer">
      <img class="rounded-md" :src="image" alt="" />
      <div class="pt-4 font-sans text-white text-[17px]">{{ title }}</div>
      <div class="pt-1 pb-3 font-sans text-gray-400 text-[14px]">
        {{ title }}
      </div>
    </div>
  </RouterLink>
</template>
