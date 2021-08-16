<template>
	<div class="container-top">
		<Card :title="this.title" :price="this.price" />
		<Card :title="this.title" :price="this.price" />
	</div>
</template>

<script>
import Card from './Card.vue';
export default {
	name: 'Top',
	components: {
		Card,
	}, 
	data() {
		return {
			title: 'Menu 1',
			price: '5 dollars',
		}
	}
}
	
</script>

<style lang="less" scoped>
.container-top {
	padding-bottom: 45px;
	display: flex;
	justify-content: center;
	align-items: center;
}
</style>