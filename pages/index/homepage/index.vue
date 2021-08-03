<template>
	<view class="homepage">
		<view class="banner"> 
			<text class="slogan">套餐<span class="highlight">9.9元</span>起 <span class="highlight">免</span>配送费</text>
			<image class="hbg" src="../../../static/img/tabbar/user.jpg" mode="scaleToFill"></image>
			<input type="input" class="search" maxlength="30"  focus placeholder="请输入商家或商品名称" />
		</view>
		<view class="container">
			<view class="quick-menu">
				<caidan title="天天领现金" image="../../../static/img/tabbar/balance.png"></caidan>
				<caidan title="领免拼单券" image="../../../static/img/tabbar/balance.png"></caidan>
				<caidan title="附近拼单" image="../../../static/img/tabbar/balance.png"></caidan>
				<caidan title="0元吃大餐" image="../../../static/img/tabbar/balance.png"></caidan>			
			</view>
			
		</view>
	</view>
	
	
	
</template>

<script>
	import Caidan from '../../../components/caidan/caidan.vue'
	export default {
		data() {
			return {
				
			}
		},
		components:{ Caidan },
		methods: {
			
		}
	}
</script>

<style scoped lang='scss'>
	.homepage{
		.hbg{
			width: 100%;
		}
		.banner {
			position: relative;
			.slogan {
				position: absolute;
				top: 0;
				left: 0;
				right: 0;
				text-align: center;
				margin: auto;
				z-index: 9;
				color: red;
			}
			.search {
				position: absolute;
				bottom: 60px;
				width: 80%;
				left: 0;
				right: 0;
				text-align: center;
				margin: auto;
				z-index: 9;
				color: red;
			}
			input{
				flex: 1;
				margin-left: 16rpx;
				padding: 0 28rpx;
				height: 70rpx;
				line-height: 70rpx;
				font-size: 30rpx;
				color: #333;
				background-color: #f5f5f5;
				border-radius: 100rpx;
			}
		}
		
		.container {
			position: relative;
			top: -40rpx;
			.quick-menu {
				margin: 0 10rpx;
				border-radius: 5px;
				display: flex;
				justify-content: space-around;
				background-color: #fff;
			}
		}
		
	}
	
	
	
	
	
</style>
