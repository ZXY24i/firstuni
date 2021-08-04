<template>
	<view class="menu1">
		<image class="imgs" src="../../static/img/caidan2.jpg"></image>
		<view class="right">
			<view class="R-top">
				<text class="tit">秋道石锅拌饭</text>
				<view class="two">
					<text class="grade"> <span class="sp2">4.7</span> 秋道寿司（日式便当）</text>
					<text class="distance">46分钟 2.2Km</text>
				</view>
			</view>
			
			<view class="count">
				<text class="num"><span class="sp3">￥</span>12.9 <del class="old">￥13</del></text>
				<view class="number">
					<text class="amount">已拼10+份</text>
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
		background-color: #fff;
		padding:10px;
		margin: 25rpx;
		border-radius:15rpx
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
	.old{
		color: #7f7f7f;
		font-size: 14rpx;
		
	}
	.sp3{
		font-size: 12rpx;
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
</style>
