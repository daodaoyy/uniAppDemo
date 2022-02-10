<template>
	<view class="content">
		<input class="uni-input phone" type="number" placeholder="请输入用户名/手机号/邮箱账号" />
		<input class="uni-input password" password type="text" placeholder="请输入密码" />
		<view class="protocol">
			<span>已阅读并同意<a>《用户协议》</a>、<a>《隐私权政策》</a></span>
		</view>
		<button class="login-btn">登录</button>
		<!-- <image class="logo" src="/static/logo.png"></image>
		<view class="text-area">
			<text class="title">{{title}}</text>
		</view> -->
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello world'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		padding-top: 120rpx;
	}
	.uni-input {
		width: 80%;
		border: 1rpx #555555 solid;
	    height: 80rpx;
		line-height: 80rpx;
		font-size: 24rpx;
		text-indent: 2em;
		text-align: center;
	}
	.phone,
	.password {
		margin-bottom: 70rpx;
	}
	.protocol {
		margin-bottom: 70rpx;
	}
	.protocol span {
		display: flex;
		font-size: 26rpx;
	}
	.login-btn {
		width: 80%;
		background-color: #192B93;
		color: #FFFFFF;
		font-size: 32rpx;
		border-radius: 8rpx;
		height: 100rpx;
		line-height: 100rpx;
	}
</style>
