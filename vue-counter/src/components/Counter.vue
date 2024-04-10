<script setup>
import { ref } from 'vue';

const count = ref(0);

function increment() {
	count.value++;
}

// function updateCount(event) {
// 	count.value = Number(event.target.value);
// }
</script>

<template>
	<div>
		<h1>{{ count }}</h1>
		<button @click="increment">+</button>
		<!-- <input @input="updateCount" /> -->
		<input v-model="count" />
	</div>
</template>
