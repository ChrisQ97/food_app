<template>
	<div class="wrapper">
		<div class="item">
			<a href="/wine">
				<i class='bx bxs-wine bx-lg' ></i>
			</a>
		</div>
		<div class="item">
			<a href="/dish">
				<i class='bx bx-dish bx-lg' ></i>
			</a>
		</div>
		<div class="item">
			<a href="/cake">
				<i class='bx bxs-cake bx-lg' ></i>
			</a>
		</div>
		<div class="item">
			<a href="/menu">
				<i class='bx bx-food-menu bx-lg' ></i>
			</a>
		</div>
		<div class="item">
			<a href="/drink">
				<i class='bx bxs-drink bx-lg' ></i>
			</a>
		</div>
		<div class="item">
			<a href="/beer">
				<i class='bx bxs-beer bx-lg' ></i>
			</a>
		</div>
		<div class="item">
			<a href="/pizza">
				<i class='bx bxs-pizza bx-lg' ></i>
			</a>
		</div>
		<div class="item">
			<a href="/cookie">
				<i class='bx bxs-cookie bx-lg' ></i>
			</a>
		</div>

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
	justify-content: space-between;
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
	color: red;
	background-color: #faf8f8;
	color: black;
	margin: 5px;
	border-radius: 25px;
	align-items: center;
	padding-top: 20px;

}
a {
	color: #5a5756;
}
a:hover {
	color: white;
}
.item:hover {
	color: blue;
	background-color: #f1420f;
}
</style>