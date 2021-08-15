<template>
	<div class="combo-header">
		<div class="text-menu-featured">
			<h1>Hamburguer</h1>
			<p>1 Hamburguer with extra cheese</p>
		</div>
		<div class="image-menu-featured">
			<img src="https://images.unsplash.com/photo-1586816001966-79b736744398?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" alt="">
		</div>
	</div>
</template>
<script>
	export default {
		name: 'Featured'
	}
</script>
<style languaje="less" scoped>
.combo-header {
	margin: 50px;
	background-color: #f1420f;	
	padding: 75px;
	border-radius: 50px;
	color: white;
	font-weight: bold;
	display: flex;
	align-items: center;
	justify-content: center;
}
h1 {
	font-size: 8vw;
}
p {
	font-size: 3vw
}
.image-menu-featured {
  max-width: 100%;
  height: auto;
}
img {
	width: 60%;
	object-fit: cover;
}
</style>