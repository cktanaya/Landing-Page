<template>
	<navbar-element></navbar-element>
	<home-view></home-view>
	<footer-element></footer-element>
</template>

<script>
import NavbarElement from '@/components/NavbarElement.vue';
import FooterElement from '@/components/FooterElement.vue';
import HomeView from '@/HomeView.vue';

export default {
	components: {
		HomeView,
		FooterElement,
		NavbarElement
	}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body{
  background-image: url("@/assets/LIB.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
