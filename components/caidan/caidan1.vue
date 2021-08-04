<template>
	<view class="list-cell">
		<image class="cell-img" :src="image"></image>
		<text class="cell-title">{{ title }}</text>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		props:{
			title: {
				type: String,
				default: '菜单'
			},
		    image: {
				type: String,
				default: 'image'
			},
		},
		methods: {
		}
	}
</script>

<style>
	.list-cell{
		display: flex;
		flex-direction: column;
		margin-right: 10rpx;
	}
	.cell-img{
		width: 40px;
		height: 40px;
		margin-bottom: 8rpx;
		margin: 0 auto;
	}
	.cell-title{
		font-size: 24rpx;
	}
</style>
