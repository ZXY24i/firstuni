<template>
	<view clss="menu">
		<image class="img" :src="image"></image>
		<view>
			<title class="tit">{{title}}</title>
			<view class="two">
				<small class="grade">{{text}} </small>
				<small class="distance">{{time}}分钟{{dis}}Km</small>
			</view>
			<view class="count">
				<text class="num">{{price}}</text>
				<text class="amount">已拼{{number}}+份
				<em>马上抢</em>
				</text>
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
		props:{
			image: {
				type: String,
				default:''
			},
			title: {
				type: String,
				default: 'biaoti'
			},
			text: {
				type: String,
				default: 'shopname'
			},
			time:{
				type: number,
				default: 'time'
			},
			dis:{
				type:number,
				default: ''
			},
			price: {
				type:number,
				default:'10'
			},
			number: {
				type:number,
				default: ''
			}
			
			
		}
	}
</script>

<style>
</style>
