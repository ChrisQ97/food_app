<template>
	<div class="container-card">
		<h2>{{ title }}</h2>
		<h3>{{ price }}</h3>
		
		<img src="https://cdn7.kiwilimon.com/recetaimagen/13003/640x426/th5-640x426-5707.jpg.webp" alt="image">
		<i class='bx bx-plus-circle bx-lg'></i>
	</div>
</template>
<script>
	export default {
		name: 'Card',
		props: {
			title: String,
			price: String,

		},
	}
</script>

<style type="less" scoped>
.container-card {
	padding: 10px;
	background-color: #faf8f8;
	border-radius: 50px;
	margin: 25px;

}
h2 {
	margin-top: 25px;
	font-size: 6vw;
	color: #5a5756;
}
h3 {
	color: #5a5756;
	font-size: 4vw;
}

img {
	width: 60%;
	object-fit: cover;
	margin-bottom: 20px;
}
.bx {
	color: green;

}

</style>