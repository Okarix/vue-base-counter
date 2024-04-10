<script>
export default {
	data() {
		return {
			count: 0,
		};
	},
	methods: {
		increment() {
			this.count++;
		},
	},
};
</script>

<template>
	<div>
		<h1>{{ count }}</h1>
		<button @click="increment">+</button>
	</div>
</template>
