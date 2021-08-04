<template>
	<view class="homepage">
		<view class="banner"> 
			<text class="slogan">套餐   <span class="highlight " style="pre-wrap">9.9元    </span>起  <span class="highlight">免</span>配送费</text>
			<image class="hbg" src="../../../static/img/user.jpg" mode="scaleToFill"></image>
			<input type="input" class="search" maxlength="30"  focus placeholder="请输入商家或商品名称" />
		</view>
		<view class="container">
			<view class="quick-menu">
				<caidan title="天天领现金" image="../../../static/img/balance.png"></caidan>
				<caidan title="领免拼单券" image="../../../static/img/balance.png"></caidan>
				<caidan title="附近拼单" image="../../../static/img/balance.png"></caidan>
				<caidan title="0元吃大餐" image="../../../static/img/balance.png"></caidan>			
			</view>
			<view class="mini-menu">
				<caidan1 title="推 荐" image="../../../static/img/2.jpg"></caidan1>
				<caidan1 title="炒菜盖饭" image="../../../static/img/2.jpg"></caidan1>
				<caidan1 title="炒饭拌饭" image="../../../static/img/2.jpg"></caidan1>
				<caidan1 title="饺子粥饼" image="../../../static/img/2.jpg"></caidan1>
				<caidan1 title="日韩料理" image="../../../static/img/2.jpg"></caidan1>
			</view>
			<view>
				<menu1 class=""></menu1>
				<menu2> </menu2>
			</view>
		</view>
	</view>
	
	
	
</template>

<script>
	import Caidan from '../../../components/caidan/caidan.vue'
	import Caidan1 from '../../../components/caidan/caidan1.vue'
	import Menu1 from '../../../components/caidan/one-menu.vue'
	import Menu2 from '../../../components/caidan/two-menu.vue'
	export default {
		data() {
			return {
				
			}
		},
		components:{ Caidan, Caidan1 , Menu1 ,Menu2 },
		
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
				font-size: 30px;
				color: #fff;
				text-align: center;
				margin: auto;
				z-index: 9;
			}
			.highlight{
				color:#fde632
			}
			.search {
				position: absolute;
				bottom: 60px;
				width: 80%;
				left: 0;
				right: 0;
				/* text-align: center; */
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
			background-color: #e5e5e5;
			.quick-menu {
				margin: 0 25rpx;
				border-radius: 5px;
				display: flex;
				justify-content: space-around;
				background-color: #fff;
			}
			.mini-menu {
				margin:20px 10px;
				display:flex;
				margin-right: 100rpx;
				justify-content: space-between;
				
			}
		}
		
	}
	
	
	
	
	
</style>
