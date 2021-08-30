<template>
	<button style="btn-primary" @click="click">
		Click ButtonVue {{ count }} times
	</button>
</template>

<script>
export default {
	name: "ButtonVue",
	data() {
		return {
			count: 0,
		};
	},
	methods: {
		click() {
			this.count++;
		},
	},
};
</script>

<style scoped>
button {
	margin-top: 4%;
}
</style>
