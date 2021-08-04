<template>
	<view class="menu1">
		<image class="imgs" src="../../static/img/caidan1.jpg"></image>
		<view class="right">
			<view class="R-top">
				<text class="tit"><span class="sp1">超级补贴</span> 孜然麻辣烤肉+豆角烧茄子双拼</text>
				<view class="two">
					<text class="grade"> <span class="sp2">4.5</span> 爱商大盘鸡&牛肉堡</text>
					<text class="distance">46分钟 2.2Km</text>
				</view>
			</view>
			
			<view class="count">
				<text class="num"><span class="sp3">￥</span>9.3</text>
				<view class="number">
					<text class="amount">已拼100+份</text>
					<text >马上抢</text>
				</view>
			</view>
		</view>
	</view>
</template>
<script>
	export default {
		data(){
			return {
			}
		},
		methods: {
		}
	}
</script>
<style scoped lang='scss'>
	view{
		display: flex;
	}
	.menu1{
		margin:10px;
		background-color: #fff;
		padding:10px;
		border-radius: 25rpx;
	}
	.imgs{
		width:30%;
		border-radius:10px;
	}
	.right{
		/* display: flex; */
		flex:1;
		flex-direction: column;
		margin:14rpx;
		justify-content: space-between;
	}
	.R-top{
		flex-direction: column;
	}
	.tit{
		font-size: 26rpx;
	}
	.sp1{
		font-size: 22rpx;
		background-color: red;
		color:#fff;
		padding:2px;
		border-radius:5px;
	}
	.two{
		margin:5rpx 0px;
		font-size:small;
		color:#686868;
		display: flex;
		justify-content:space-between ;
		.grade{
			max-width: 130px;                      
			white-space: nowrap;                
			overflow: hidden;                       
			text-overflow: ellipsis;                
			cursor: pointer;                         
		}
		.sp2{
			display: inline-block;
			color:#ff6315;
			margin-right: 10px;
		}
	}
	.count{
		display:flex;
		justify-content:space-between;
	}
	.num{
		font-size: 45rpx;
		color:red;
	}
	.number{
		flex-direction:column;
		color:#fff;
		background-color:#ff0000;
		border-radius: 8rpx;
		padding: 6rpx;
		justify-content:center;
		text-align:center;
		.amount{
			font-size:14rpx;
		}
	}
	.sp3{
		font-size: 12rpx;
	}
</style>
