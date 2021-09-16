<!-- @format -->

<template>
	<div id="app">
		<Card />
	</div>
</template>

<script>
	import Card from "./components/Card.vue";
	export default {
		name: "App",
		components: {
			Card,
		},
	};
</script>

<style>
	#app {
		text-align: center;
	}
</style>
