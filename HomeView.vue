<template>
	<main-section></main-section>
	<about-section></about-section>
	<contact-section></contact-section>
</template>

<script>
import MainSection from '@/sections/MainSection.vue';
import AboutSection from '@/sections/AboutSection.vue';
import ContactSection from '@/sections/ContactSection.vue';

export default {
	components: {
		MainSection,
		AboutSection,
		ContactSection,
	}
}
</script>

<style scoped>


</style>