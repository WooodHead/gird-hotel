<template>
	<div class="login">
		<input type="text" placeholder="手机号或者卡号"/>
		<input type="text" placeholder="密码(4到11位字母、数字)"/>
		<button class="log">登录</button>
		<a href="#">忘记密码？</a>
		<button class="logup">立即注册</button>
	</div>
</template>

<script>

</script>

<style scoped="">
	input,button,a{
		display: block;
		margin: 0 auto;
	}
	input{
		width: 100%;
		margin: 20px auto;
		padding: 15px 5px 5px;
		border: none;
		border-bottom: 1px solid #C0C0C0;
		font-size: 14px;
	}
	button.log{
		width: 100%;
		margin: 0 auto;
		color: white;
		font-size: 16px;
		text-align: center;
		background-color: #2395FF;
		border-radius: 10px;
		line-height: 40px;
	}
	a{
		width: 100%;
		font-size: 14px;
		text-align: center;
		margin: 20px 0;
		text-decoration: underline;
	}
	button.logup{
		background-color: #fff;
		width: 20%;
		padding: 5px 0;
		font-size: 14px;
		color: orange;
		border: 1px solid orange;
	}
</style>