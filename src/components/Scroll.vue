<template>
	<div class="wrapper">
		<div class="item"><i class='bx bxs-wine bx-lg' ></i></div>
		<div class="item"><i class='bx bx-dish bx-lg' ></i></div>
		<div class="item"><i class='bx bxs-cake bx-lg' ></i></div>
		<div class="item"><i class='bx bx-food-menu bx-lg' ></i></div>
		<div class="item"><i class='bx bxs-drink bx-lg' ></i></div>
		<div class="item"><i class='bx bxs-beer bx-lg' ></i></div>
		<div class="item"><i class='bx bxs-pizza bx-lg' ></i></div>
		<div class="item"><i class='bx bxs-cookie bx-lg' ></i></div>

	</div>
</template>
<script>
export default {
	name: 'Scroll',
}	
</script>

<style languaje="less" scoped>	
.wrapper {
	align-items: center;
	justify-content: center;
	max-height: 150px;
	padding-bottom: 50px;
	display: flex;
	margin: 10px;
	overflow-x: auto;
	

}
.item {
	min-width: 120px;
	height: 120px;
	line-height: 120px;
	text-align: center;
	background-color: #faf8f8;
	color: black;
	margin: 5px;
	border-radius: 25px;
	align-items: center;
	padding-top: 20px;
    &:hover {
      color: rgba(255,131,62);
    }

}

</style>