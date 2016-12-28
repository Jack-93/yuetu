<template>
	<div class="home">
		<div class="nav">
			<div class="nav-left">全国<i></i></div>
			<div class="nav-middle">首页 </div>
			<div class="nav-right"></div>
		</div>
	</div>
</template>

<script>
export default {
  name: 'hello'
}
</script>

<style scoped>
.nav {
	position: relative;
	color: #fff;
	background-color: rgb(255, 148, 171);
	text-align: center;
}

.nav-left {
	position: absolute;
	top: 9px;
	left: 15px;
	font-size: 13px;
	color: #fff;
}

.nav-left i {
	display: inline-block;
	width: 12px;
	height: 6px;
	margin-left: 5px;
	margin-bottom: 1px;
	background-image: url(../../static/images/downicon.png);
	background-size: 12px 6px;
	font: none;
}

.nav-middle {
	padding: 5px 0 10px 0;
	font-size: 18px;
	font-weight: bold;
}

.nav-right {
	position: absolute;
	top: 5px;
	right: 15px;
	width: 20px;
	height: 20px;
	background-image: url(../../static/images/telphone.png);
	background-size: 20px 20px;
}
</style>