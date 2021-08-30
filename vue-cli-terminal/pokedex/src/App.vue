<template>
	<div id="app">
		<ButtonVue></ButtonVue> <br />
		<button @click="count++">Click</button>
		{{ count }}
		<button @click="count++">Click</button>
	</div>
</template>

<script>
import ButtonVue from "./components/ButtonVue.vue";

export default {
	name: "App",
	components: {
		ButtonVue,
	},
	data() {
		return {
			count: 0,
		};
	},
};
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	align-content: center;
	display: -moz-grid-group;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>
