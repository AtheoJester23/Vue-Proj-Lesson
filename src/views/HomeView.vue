<script setup>
    import HeroVue from "@/components/Hero.vue";
    import HomeCardsVue from "@/components/HomeCards.vue";
    import JobListings from "@/components/JobListings.vue";
</script>

<template>
    <HeroVue title="This is title" daSubtitle="Lorem ipsum something something"/>
    <HomeCardsVue/>  
    <JobListings :limit="3" :showButton="true"/>
</template>