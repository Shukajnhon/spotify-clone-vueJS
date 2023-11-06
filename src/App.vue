<script setup>
import {ref, onMounted} from 'vue';
import {RouterLink, RouterView} from 'vue-router';

import ChevronUp from 'vue-material-design-icons/ChevronUp.vue';
import ChevronDown from 'vue-material-design-icons/ChevronDown.vue';
import ChevronRight from 'vue-material-design-icons/ChevronRight.vue';
import ChevronLeft from 'vue-material-design-icons/ChevronLeft.vue';

let openMenu = ref(false);
</script>

<template>
  <div>
    <div
      class="w-[calc(100%-240px)] h-[60px] fixed right-0 z-20 bg-[#101010] bg-opacity-80 flex items-center justify-between"
    >
      <div class="flex items-center ml-6">
        <button
          type="button"
          class="rounded-full bg-black p-[1px] cursor-pointer"
        >
          <ChevronLeft fillColor="#fff" :size="30" />
        </button>

        <button
          type="button"
          class="rounded-full bg-black p-[1px] cursor-pointer ml-4"
        >
          <ChevronRight fillColor="#fff" :size="30" />
        </button>
      </div>

      <button
        @click="openMenu = !openMenu"
        :class="openMenu ? 'bg-[#282828]' : '#bg-black'"
        class="bg-black hover:bg-[#2828282] rounded-full p-0.5 mr-8 mt-0.5 cursor-pointer"
      >
        <div class="flex items-center">
          <img
            class="rounded-full"
            width="27"
            src="https://yt3.ggpht.com/yti/ADpuP3OM_eyaOVdYr1XQT2lt2P2nspljwZhKmfWtn-ywmRk=s88-c-k-c0x00ffffff-no-rj"
            alt=""
          />
          <div class="text-white text-[14px] ml-1.5 font-semibold">
            Peter Pham
          </div>
          <ChevronDown
            v-if="!openMenu"
            @click="openMenu = true"
            fillColor="#fff"
            :size="25"
          />
          <ChevronUp
            v-else="!openMenu"
            @click="openMenu = false"
            fillColor="#fff"
            :size="25"
          />
        </div>
      </button>
    </div>
  </div>
</template>
