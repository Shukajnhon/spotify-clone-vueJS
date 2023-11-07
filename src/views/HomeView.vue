<script setup>
import HomeCard from '../components/HomeCard.vue';
</script>

<template>
  <div class="p-8">
    <button
      type="button"
      class="text-2xl font-semibold text-white cursor-pointer hover:underline"
    >
      Podcasts to make you smarter
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="https://picsum.photos/id/30/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        image="https://picsum.photos/id/45/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden md:block"
        image="https://picsum.photos/id/65/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden lg:block"
        image="https://picsum.photos/id/67/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden xl:block"
        image="https://picsum.photos/id/100/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
    </div>
  </div>

  <div class="p-8">
    <button
      type="button"
      class="text-2xl font-semibold text-white cursor-pointer hover:underline"
    >
      Recommended radio
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="https://picsum.photos/id/30/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        image="https://picsum.photos/id/45/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden md:block"
        image="https://picsum.photos/id/65/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden lg:block"
        image="https://picsum.photos/id/67/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden xl:block"
        image="https://picsum.photos/id/100/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
    </div>
  </div>

  <div class="p-8">
    <button
      type="button"
      class="text-2xl font-semibold text-white cursor-pointer hover:underline"
    >
      Recommended songs
    </button>

    <div class="py-1.5"></div>

    <div class="flex items-center">
      <HomeCard
        image="https://picsum.photos/id/30/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        image="https://picsum.photos/id/45/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden md:block"
        image="https://picsum.photos/id/65/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden lg:block"
        image="https://picsum.photos/id/67/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
      <HomeCard
        class="hidden xl:block"
        image="https://picsum.photos/id/100/300/300"
        title="Title is here"
        subTitle="Subtitle is here"
      />
    </div>
  </div>
</template>
