<script setup>
import allTracksSvg from '@/shared/images/alltracks.svg';
import BaseSectionTitle from "@/ui/BaseSectionTitle.vue";
import {Playlist} from "@/modules/Playlists/index.js";
</script>

<template>
  <main class="container-fluid p-md-5 mb-5 pb-5">
    <BaseSectionTitle
        header="Вся музыка сервиса"
        :src="allTracksSvg"
    />
    <Playlist/>
  </main>
</template>