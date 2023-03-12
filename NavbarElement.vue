<template>
    <nav class="w-screen fixed bg-opacity-20 bg-white p-4 lg:px-50 flex justify-between z-100">
		<div class="h-full flex flex-col justify-center">
			<p class="absolute top-5 left-40 font-semibold">Research</p>
			<p class="absolute bottom-10 left-40 font-light">Compendium</p>
		</div>

		<div class="absolute bottom-100 left-5 overflow-hidden">
			<img src="@/assets/logo.png" alt="img" class="h-full">
		</div>

		<button role="menubar" class="md:hidden" @click="navToggle()">
			<i class="fa-solid fa-bars text-2xl"></i>
		</button>

		<div class="absolute left-50 right-100 translate-y-16 bg-opacity-90 bg-white md:bg-none md:bg-opacity-0 shadow hidden md:flex flex-col gap-4 items-center p-4 md:flex-row md:static md:shadow-none md:translate-y-0" role="menu" aria-expanded="false">
			<a href="#" role="menuitem">
				<p class="mx-4">Home</p>
			</a>

			<a href="about-section" role="menuitem">
				<button class=" transition">
				<p class="mx-4">About</p></button>
			</a>

			<button class="btn" role="menuitem">
				Explore
			</button>
		</div>
	</nav>
</template>

<script>

export default {
    methods: {
        navToggle() {
			let menu = document.querySelector("[role='menu']");
			let isExpanded = menu.getAttribute('aria-expanded');
			menu.setAttribute('aria-expanded', !isExpanded);
			menu.classList.toggle('hidden');
			menu.classList.toggle('flex');
		}
    }
}
</script>

<style>

</style>