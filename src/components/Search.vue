<template>
	<div class="search">
		<input type="text" placeholder="Find what you want">
		<div class="icon-input">
			<i class="bx bx-search bx-sm"></i>
		</div>
	</div>
</template>
<script>
	export default {
		name: 'Search',
	}
</script>
<style lang="less">
.search {
	display: flex;
	position: relative;
	align-item: center;
	margin: 15px;
	input {
		width: 100%;
		padding: 20px;
		background-color: #faf8f8;
		border: 0;
		color: black;
		wight: bold;
		outline: none;
		border-radius: 40px;
		padding-left: 40px;
		font-size: 20px;
	}
	.icon-input {
	position: absolute;
	padding-top: 18px;
	padding-left: 10px;
	}
}


</style>